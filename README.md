Car Rental System - README

Overview

The Car Rental System is a Java-based application designed using Object-Oriented Programming (OOP) principles. It allows users to rent cars, manage bookings, and handle administrative tasks like adding or removing cars.

Features

1. User Registration and Login

Users can register, log in, and access their rental history.



2. Car Management

Add, remove, or update car details (Admin feature).

View available cars for rent.



3. Rental Booking

Book cars based on availability.

Return cars and calculate rental charges.



4. Rental History

View past rentals and payment details.




OOP Concepts Used

1. Encapsulation

All data members are private and accessed via getter and setter methods.

Example: Car, User, and Booking classes encapsulate their respective properties.



2. Inheritance

Common features are abstracted into parent classes.

Example: Admin and Customer inherit from a User class.



3. Polymorphism

Overloading and overriding methods for flexibility.

Example: calculateRentalCost() method behaves differently for different car types.



4. Abstraction

Interfaces and abstract classes hide implementation details.

Example: Payment interface defines methods like processPayment() for different payment methods.



5. Composition

Classes like Booking have references to User and Car objects.





Future Enhancements

1. Add a graphical user interface (GUI) for better usability.

2. Integrate a database for persistent storage.

3. Add advanced search and filter options for cars.

4. Include payment gateways for online payments.



Author
Chhavi Gupta

For questions or feedback, contact me at chhavigupta0121@gmail.com
