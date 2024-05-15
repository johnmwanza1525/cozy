Project Overview

The Django hotel room booking project for AB_cozy apartments will involve the creation of a user-friendly and efficient web application that allows users to book rooms online, manage reservations, and handle payments. The application will feature an administration panel for managing services, user account creation, online reservation, and payment processing via Visa card and Mpesa using the Daraja API. The project will also support guest bookings without account creation and provide necessary notifications for payments and reservations.
Project Specifications
Key Features

    User Registration and Authentication:
        User can create an account, log in, and manage their reservations.
        Receptionists can log in to manage bookings.

    Room Management:
        Display all available rooms.
        Rooms should be marked as booked if reserved, preventing double booking.
        Daily charges for each room type.

    Reservation System:
        Users can book rooms online.
        Calculate total reservation cost during checkout.
        Receptionists can make reservations on behalf of customers.
        Option for guests to book without creating an account.

    Payment Integration:
        Payment via Visa card.
        Payment via Mpesa using Daraja API.
        Payment confirmation and notifications (SMS and Email).

    Notification System:
        Send SMS and email receipts to customers upon payment confirmation.
        Notify receptionist of successful payments.

    Administration Panel:
        Manage rooms, reservations, and other services.
        View and manage payments and customer information.

Technical Stack

    Backend: Django
    Frontend: HTML, CSS, JavaScript (Bootstrap for UI components)
    Database: PostgreSQL or MySQL
    Payment Gateway: Mpesa Daraja API, Visa payment integration
    Messaging: Twilio for SMS, Django Email for email notifications

Project Structure
1. Setting Up the Django Project

    Create a new Django project and app.
    Configure the database settings.

