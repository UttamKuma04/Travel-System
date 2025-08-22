# Travel Lykke 
![alt text](<Screenshot 2025-08-22 094235.png>)
A Django-based travel booking system supporting flights, trains, and buses.  
Uses **MySQL** as the database.

## Features
- User Authentication (Signup, Login, Logout, Profile Update)
- Users can create their user account.
- User can update their profile.
- Search & Book Travel Options
- Users can cancel their booked tickets.
- Users can view their previously booked tickets (Both confirmed and cancelled tickets).
- Admin Panel for managing bookings.
- As-you-type Search
- MySQL integration with Django ORM


## Files & Directories

    Travel_Booking - project directory.
    urls.py - This file handles all the URLs of the project.
    app - main application directory.
    static - contains all static content.
    
    templates/app
        base.html - Home page template.
        booking_history.html - Template for Showing Booking history.
        booking_success.html - Template for Showing Ticket Confirmation.
        travel_list.html - Template For Showing Filtered Availble Tickets.
        travel_option.html - Template for showing selected flight,train, bus and reading Travellers data.
        booking_success.html - Template for showing bookings done by a user.

    registration
        login.html - Login user page.
        register.html - Register user page.
        profile.html - User Profile page.
    admin.py - Contains some models for access to the Django administrator.
    models.py - All models used in the application are created here.
    urls.py - This file handles all the URLs of the web application.
    views.py - This file contains all the application views.
    requirements.txt - This file contains all contains all the python packages that needs to be installed to run this web application.
    manage.py - This file is used basically as a command-line utility and for deploying, debugging, or running our web application.

## Setup
1. Clone repo:
   ```bash
   git clone https://github.com/UttamKuma04/Travel-System.git
   cd your-repo-name

2.python -m venv .venv

3.pip install -r requirements.txt

4.pip install -r requirements.txt

5.python manage.py migrate

6.python manage.py runserver

## Justification
1.Mobile responsive webpages.
2.More complex models.
3.More interatactive because webpages use ajax functionality (eg., fetch) written in javascript.
