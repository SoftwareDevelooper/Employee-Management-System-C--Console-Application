# Employee-Management-System-C++ Console-Application
This project is a basic Employee Management System developed in C++. It allows users to register, log in as employees, view salary/leave/insurance information, and includes a special admin (boss) interface.
Features

✔ User Registration

Employees can register by selecting their employment status (full-time, part-time, intern).

Each user receives a unique personal number used for login.

Registered user information is stored in a .txt file.

✔ Employee Login

Employees log in using:

Personal number

Username

Password

After logging in, they can choose one of the following operations:

Calculate monthly salary

Check monthly leave entitlement

Calculate insurance cost

All calculations are based on the employee's status.

✔ Boss Login

Access is granted only with a special personal number (0001).

The boss can:

View all registered employees

Display their usernames and employment status

Access boss-specific salary, leave, and insurance calculations

✔ Object-Oriented Design

The system is organized using several classes:

EmployeeInfo — handles salary, leave, and insurance calculations

UserMemory — manages user data, registration, and login

Boss — provides administrator-level features

MainMenu — main interface and menu navigation
