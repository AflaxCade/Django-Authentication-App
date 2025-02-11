# Django Authentication App

This is a Django-based authentication app that uses `django-allauth` and `htmx` to provide a seamless authentication experience. The app supports user sign-up, sign-in, and sign-out, along with profile management and account settings.

## Features

- **User Authentication:**
  - Sign up with email verification
  - Sign in and sign out
  
- **Profile Management:**
  - View profile (profile image, username, display name, description)
  - Edit profile (update profile image, display name, and description)
  
- **Account Settings:**
  - Update email address
  - Verify email
  - Delete account

## Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/AflaxCade/Django-Authentication-App.git
   cd Django-Authentication-App
   ```

2. **Create a virtual environment and activate it:**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\ctivate`
   ```

3. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

4. **Apply database migrations:**
   ```sh
   python manage.py migrate
   ```

5. **Create a superuser (optional):**
   ```sh
   python manage.py createsuperuser
   ```

6. **Run the development server:**
   ```sh
   python manage.py runserver
   ```


## Usage

- **Sign up:** Users can register using their email.
- **Sign in:** Users can log in using their email and password.
- **Profile Page:** Displays user details including profile image, username, display name, and description.
- **Edit Profile Page:** Allows updating profile image, display name, and description.
- **Settings Page:** Users can update or verify their email and delete their account.

## Dependencies

- Django
- django cleanup
- django-allauth
- htmx
- pillow

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
