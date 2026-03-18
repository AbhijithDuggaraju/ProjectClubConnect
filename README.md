# ProjectClubConnect
This project is a command-line based application that manages college club activities, including club registration, member management, event handling, and feedback collection. It demonstrates the use of core data structures along with database integration.

Overview

The system allows students to register for clubs, participate in events, and submit feedback, while management can approve requests, manage clubs, and oversee activities. It integrates multiple data structures with persistent storage using SQLite.

Features

Student and management login system

Club registration and approval workflow

Member registration with approval queue

Event creation and registration

Feedback submission and viewing

Persistent storage using SQLite database

Data Structures Used

Linked List

Stores and manages club records

Queue (FIFO)

Handles pending member registration approvals

Stack (LIFO)

Tracks recent event registrations

Deque

Maintains event registration queue

Technologies Used

Python

SQLite (database)

Standard libraries:

sqlite3

hashlib

datetime

collections

Project Structure
CollegeClubSystem/
│── main.py                  # Main application file
│── club_registration.db     # SQLite database (auto-created)
│── README.md
Installation

Install Python (version 3.10 or higher recommended).

No external dependencies are required.

Usage

Run the program:

python main.py
Functional Modules
Student

View clubs and details

Register for clubs

Submit feedback

Propose new clubs

Register for events

Management

Approve club proposals

Approve member registrations

Update club details

Add events

View feedback

Database Schema

Tables used:

clubs

members

feedback

pending_clubs

events

event_registrations

Input Validation

Email format validation

Password hashing using SHA-256

Safe integer input handling

Date validation for events

Security Features

Passwords stored as hashed values

Login authentication for students and management

Unique email constraint for users

Future Improvements

Graphical user interface (GUI)

Web-based deployment

Role-based authentication system

Email notifications for approvals

Advanced search and filtering

Author

Abhijith Duggaraju
B.Tech Information Technology
Interest areas: Software Development, Data Structures, Machine Learning
