
# [Blog App ](https://himanshuone.pythonanywhere.com/)

This is a basic blog application built with Django. It allows users to create, read, update, and delete blog posts.


## Features

- User authentication (registration, login, logout)
- Create, read, update, and delete blog posts
- Admin panel
- List of all blog posts
- View individual blog post details



## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

## Tech Stack

**Client:** HTML, CSS, JS

**Server:** Django




## Requirements

- Python 3.x
- Django 3.x or higher

## Run Locally
 1. Clone the repository:

```bash
git clone https://github.com/yourusername/django-blog-app.git
cd django-blog-app 
```

2. Create and activate a virtual environment:
```bash
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate` 
```

3. Install the dependencies:
```bash
pip install -r requirements.txt
```
4. Apply migrations:

```bash
python manage.py migrate
```
5. Create a superuser:

```bash
python manage.py createsuperuser
```
6. Run the development server:

```bash
python manage.py runserver
```
7. Open your web browser and go to http://127.0.0.1:8000/ to see the app in action.
### Project Stucture:
- **blog/**: Django app for blog functionality.
  - **migrations/**: Database migrations.
  - **templates/**: HTML templates.
  - **views.py**: View functions.
  - **models.py**: Database models.
  - **urls.py**: URL routes.
  - **forms.py**: Forms.
  - **admin.py**: Admin configuration.

- **blogsite/**: Project configuration.
  - **settings.py**: Project settings.
  - **urls.py**: Project URL routes.
  - **wsgi.py**: WSGI application.
  - **asgi.py**: ASGI application.

- **manage.py**: Django management script.
- **requirements.txt**: Python dependencies.

## Authors

[Himanshu Kumar](https://linkedin.com/in/himanshuone6)


## Feedback

If you have any feedback, please reach out to us at himanshucome1@gmail.com


## Contributing

Contributions are always welcome!



