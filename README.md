# Django Posts Project

This is a simple Django project that allows users to create and view posts after logging in.

## Features

- User authentication: Users must log in to create posts.
- Create posts: Logged-in users can create posts with a title, body, and an optional image.
- View posts: Anyone can view the list of posts.

## Requirements

- Python 3.x
- Django 3.x or higher

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/django-posts-project.git
    cd django-posts-project
    ```

2. Create and activate a virtual environment:

    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

4. Set up the Django project:

    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

5. Create a superuser to access the Django admin panel:

    ```bash
    python manage.py createsuperuser
    ```

6. Run the development server:

    ```bash
    python manage.py runserver
    ```

## Usage

1. Access the application in your web browser at `http://127.0.0.1:8000/`.

2. Log in using your credentials. If you don't have an account, you can register one.

3. Once logged in, you can create a post by filling out the title, body, and optionally uploading a banner image.

4. View the list of posts, which includes the title, body, and banner image.

## Notes

- Make sure to configure your database settings in `settings.py` if you want to use a database other than the default SQLite.
- You can add custom styles to your project by modifying the CSS files in the `static/` directory.

## License

This project free and anyone can recreate.
