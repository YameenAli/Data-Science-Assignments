# Assignment 7: Object-Oriented Programming

This repository contains solutions to assignment focusing on object-oriented programming concepts in Python.

##  Vehicle Class Hierarchy

### Description
- Created a Python class named `Vehicle` with attributes `make`, `model`, and `year`.
- Implemented a method named `drive()` that prints "The vehicle is being driven."
- Created a subclass named `Car` that inherits from the `Vehicle` class and adds an attribute `fuel_type`.
- Demonstrated single class inheritance by creating an instance of the `Car` class and invoking the `drive()` method.
- Introduced a new subclass named `ElectricCar` that inherits from the `Car` class, adding an attribute `charge_time`.
- Demonstrated multilevel inheritance by creating an instance of the `ElectricCar` class and invoking the `drive()` method inherited from the `Vehicle` class.
- Created separate classes `Car`, `Motorcycle`, and `Truck`, each inheriting from the `Vehicle` class, implementing unique attributes and methods for each subclass.
- Demonstrated multiclass inheritance by creating an object of a class that inherits from multiple parent classes and invoking its methods.

## Library Management System

### Description
- Designed a class hierarchy for a library management system, including classes such as `Library`, `Book`, `Member`, and `Librarian`.
- Implemented methods for adding and removing books, checking out and returning books, and managing library members.
- The `Library` class includes attributes `name`, `books`, `members`, and `librarian`, along with methods to perform various library operations.
- The `Book` class contains attributes `title`, `author`, `isbn`, and `available`, along with methods to mark the book as checked out or returned.
- The `Member` class includes attributes `name` and `member_id`, along with a constructor to initialize member attributes.
- The `Librarian` class includes an attribute `name` and a method `manage_library()` to perform library management tasks.

## Payment Processing Module for E-commerce Platform

### Description
- Developed a payment processing module for an e-commerce platform supporting multiple payment methods such as credit card, PayPal, and cryptocurrency.
- Designed a class hierarchy with an abstract base class named `PaymentMethod` and concrete subclasses for each payment method.
- Implemented abstract methods for processing payments and validating payment information in the `PaymentMethod` base class.
- Defined specific attributes and methods for each payment method subclass to capture payment details and implement processing logic.
- Implemented polymorphic behavior by defining a common method `process_payment()` in the `PaymentMethod` base class using a magic method.
- Overrode the `process_payment()` method in each subclass to implement specific processing logic for that payment method.
- Utilized operator overloading concepts to enhance the flexibility and expressiveness of the payment processing system.
- Implemented validation methods in each subclass to ensure the correctness of payment information and utilized magic methods for attribute access and validation.
- Wrote comprehensive test cases to verify the functionality of the payment processing system, including scenarios for successful payments, invalid payment information, and edge cases.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

