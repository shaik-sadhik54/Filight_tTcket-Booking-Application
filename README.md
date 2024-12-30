# Flight_Ticket-Booking-Application
This project is a comprehensive Flight Ticket Booking Application developed in C. It provides a range of features for booking and managing flight tickets, ensuring a seamless user experience with efficient data handling and robust input validation.

Features

User Management

Account Creation: Allows users to register by entering personal details, including name, email, address, and password with validation checks.
Login System: Secures access to user profiles using email and password authentication.
Profile Management: Displays user details such as name, address, and contact information.

#Booking System

Flight Selection: Offers a wide range of domestic and international destinations with various airlines.
Trip Types: Supports one-way and round-trip bookings.
Class of Service: Includes Economy, Premium Economy, and First Class options with corresponding cost calculations.
Seat Selection: Enables users to choose seats from available options for specific flight classes.
Cost Breakdown: Provides a detailed cost analysis based on selected flight, service class, and passenger count.

Ticket Management

View Tickets: Displays detailed booking information including flight details, passenger names, class of service, seat numbers, and total cost.
Ticket Cancellation: Allows users to cancel bookings and releases reserved seats.
#Travel History
Maintains a record of all previous bookings for registered users, accessible through the travel history feature.

Technical Details

Implementation

Developed using C programming language.
Utilized doubly linked lists to manage dynamic data for customers and bookings.
Designed with modular functions for clarity and reusability.

Key Functionalities

Password Validation: Ensures secure passwords with a combination of uppercase, lowercase, and special characters.
PIN Validation: Accepts only 4-digit numerical PINs for payment authentication.
Data Structures:
Customer Node: Stores user information such as name, email, and address.
Booking Node: Maintains booking details including flight, passenger, and cost information.
Random ID Generation: Assigns unique booking IDs and customer IDs

Future Enhancements

Add graphical interface for better user experience.
Integrate a database for persistent storage of customer and booking data.
Expand features to include real-time flight availability using APIs.
