# Little Lemon Restaurant Website

A Django-based web application for the Little Lemon restaurant, allowing customers to view the menu, learn about the restaurant, and make reservations.

This Django app was created for Meta's Django Web Framework course: 
- https://www.coursera.org/learn/django-web-framework
- This course is part of the Meta Back-End Developer Professional Certificate

## Project Overview

This project is a simple Django application that creates a website for the Little Lemon restaurant with the following pages:
- Home page
- About page
- Menu page (displaying all menu items)
- Menu Item page (showing details for individual menu items)
- Booking page (for making table reservations)

## Features

- **Menu Display**: Browse all menu items alphabetically with their prices
- **Menu Item Details**: View detailed information about each menu item including description and image
- **Reservation System**: Make table reservations by filling out a form
- **Admin Interface**: Manage menu items and bookings through Django's admin panel

## Installation and Setup

1. Clone the repository or download the zip file
2. Navigate to the project directory in your terminal
3. Create a virtual environment (recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
4. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
5. Apply migrations:
   ```
   python manage.py migrate
   ```
6. Create a superuser to access the admin panel:
   ```
   python manage.py createsuperuser
   ```
7. Run the development server:
   ```
   python manage.py runserver
   ```
8. Access the website at http://127.0.0.1:8000/

## Project Structure

- **Project Name**: littlelemon
- **App Name**: restaurant
- **Key Files**:
  - `models.py`: Defines Menu and Booking models
  - `views.py`: Contains view functions for all pages
  - `urls.py`: Defines URL patterns
  - `admin.py`: Registers models for the admin interface
  - Templates in the 'templates' directory

## Admin Access

- URL: http://127.0.0.1:8000/admin/
- Default credentials (if using provided superuser):
  - Username: bistroadmin
  - Email: admin@littlelemon.com
  - Password: lemon@786!

## Technologies Used

- Django 4.1.3
- SQLite (database)
- HTML/CSS
- Bootstrap (for responsive design)

## License

This project was created as part of a Django web development course.


