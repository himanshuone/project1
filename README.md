
# [Blog App ](https://himanshuone6.pythonanywhere.com/)

This is a basic blog application built with Django. It allows users to create, read, update, and delete blog posts.


## Features

- User authentication (without user login you cannot add post or edit Post)
- Create, read, update, and delete blog posts
- Admin panel
- List of all blog posts
- View individual blog post details



## Screenshots
![Screenshot 2024-07-17 114833](https://github.com/user-attachments/assets/72d5bc05-88fc-4858-a0c6-a91334a04d1a)

![Screenshot 2024-07-17 114908](https://github.com/user-attachments/assets/0554000b-91c3-48e5-9e64-4b5ed5d4854e)

![Screenshot 2024-07-17 114928](https://github.com/user-attachments/assets/257d1d65-7a95-41d8-a5c7-839f4b1ede3c)



## Tech Stack

**Client:** HTML, CSS, JS

**Server:** Django




## Requirements

- Python 3.x
- Django 3.x or higher

## Run Locally
 1. Clone the repository:

```bash
git clone https://github.com/himanshuone/project1.git
cd project1
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



