# django-boilerplate
A Django 2.0 boilerplate to kickstart your project.

**Features:**
- Login
- Signup
- Logout
- Home Page

To use, open terminal and run the following
- `git clone https://github.com/Toluwalemi/django-boilerplate.git`
- open the directory and run the following:
    - `python manage.py makemigrations users`
    - `python manage.py migrate users`
    - `python manage.py migrate`

**Extra Info**

- This project uses a separate `users` app for authentication.
- Signup redirects to login page.
- Login page redirects to home page.
- Authentication makes use of Django in-built error messages.
- I added an error message to reject an email that already exists.

All you need to do now is create your templates and build that world class project!

Let me know if you have any questions or contributions.
