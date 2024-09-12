# Password Manager

## The Repository

This is a full-stack password manager built with Flask, PostgreSQL and React

## Screenshots

![Screenshot](./Images/sc1.png)

## Backend
- User Authentication: Secure registration and login functionality.
- CRUD Operations: Currently, create, read and delete operations are available (would have to implement a system to add a new credential and delete the old one to implement editing)
- Password Encryption: Utilizes Flask-SQLAlchemy for database interactions and ensures password security using hash functions.
- Database (PostgreSQL)

## Dashboard Features
- Register and log in securely.
- Add, view, and delete credentials.
- Maintain data privacy with encrypted passwords or choose to store in plain text (default option for demo).
- Log out securely from the dashboard.

## Data Storage
- Relational Database: Utilizes PostgreSQL to establish relationships between users and their credentials.

## Issues, Errors and Further Steps
- Security Concerns: Constant vigilance is required to address any potential vulnerabilities and ensure data security.
- User Experience: Regular feedback and user testing are crucial to enhancing the user interface and experience.
- Scalability: As the user base grows, scalability considerations need to be taken into account for optimal performance.

## Authors:
Mathieu Poirier and David Shabo 

## Acknowledgments
We appreciate the contributions of the open-source community and various libraries that facilitated the development of this Password Manager project.
