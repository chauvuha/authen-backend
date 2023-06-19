# authen-backend

# Django Backend Repository

This repository contains the backend code for a Django web application. The application serves as a backend for https://github.com/chauvuha/authen-frontend.git.

## Getting Started

To get started with the project, follow the instructions below.

### Prerequisites

- Python 3.11
- Django 4.2.1

### Installation

1. Clone the repository:
   ``` git clone https://github.com/chauvuha/authen-backend.git ```
2. The ReactJS frontend of this repository can be found at https://github.com/chauvuha/authen-frontend.git
3. virtualenv env
4. source env/bin/activate
5. pip install -r requirements.txt

### Usage
After that, to run the Django development server, use the following command:

```python manage.py runserver ```
or 
```python3 manage.py runserver```

The server will start running on http://localhost:8000/.

## Other notes

* To create superuser: ```python manage.py createsuperuser```
* Note that is_staff and is_superuser = True
* Make changes to models.py -> run ```python manage.py makemigrations``` then ```python manage.py migrate```





