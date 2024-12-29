# User Authentication System

## Project Description

This is a web application that implements a user authentication system with features like Login, SignUp, Password Reset, Change Password and User Profile Management.

## Features

1. **User Registration**: Allows users to sign up using a username, email, and password with proper validations and error handlings.
2. **User Login**: Users can log in with their username/email and password having proper validations.
3. **Dashboard**:Displays a greeting message and quick links to profile and change password along with a Logout option.
4. **Password Change**: Authenticated users can change their password.
5. **Profile Management**:Users can view their profile information (username, email, date joined, last updated).
6. **Password Reset**: Users can reset their password if they forget it by receiving a password reset email.


## Tech Stack

- **Frontend** : HTML, CSS
- **Backend**: Django
- **Database**: SQLite(can be replaced with PostgreSQL, MySQL, etc. in production).
- **Styling and Responsiveness**: Bootstrap
- **Email Functionality**: Django's email system to send password reset instructions.



## Installation and Setup

### 1. Clone the repository:

```bash
git clone https://github.com/siddharthgupta5/Django-Authentication-System.git
```

### 2. Install dependencies::

```bash
pip install -r requirements.txt
```

### 3. Environment variables: Create a .env file with the following variables:

```bash
MAIL=your_test_mail
MAIL_PASSWORD=your_test_mail_password
```

### 4. Apply migrations to setup database:

```bash
python manage.py migrate
```

### 5. Create a superuser to access the Django admin:

```bash
python manage.py createsuperuser
```

### 6. Run the development server:

```bash
python manage.py runserver
```

### 7. Access the application: 

Visit http://localhost:8000/mainapp/login in your browser.

