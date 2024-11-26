Project Overview
The Student Management System (SMS) is a web application designed to simplify the management of student information for schools, colleges, or other educational institutions. Built with Django, it allows users to perform CRUD operations. The application is user-friendly, responsive, and extensible, making it suitable for small to medium-scale institutions.

Core Modules
Admin: Login, Add Teacher, View Teacher, Edit & Delete Teacher, Approve Student, View Student, Edit & Delete Student, Logout
Teacher: Login, Edit Profile, View Student, Logout
Student: Login, Edit Profile, View Teacher, Logout

Setup Instructions
Follow these steps to set up the project on your local machine:
1. cd New_Stud
2. Create Virtual Environment
    virtualenv env
3. Activate Scripts
    Scripts\activate
    cd..
4. Go to Project
    cd project
5. Run Server
    python manage.py runserver
6. Open your browser and navigate to: http://127.0.0.1:8000/


Explanation of Features
The Student Management System includes several features designed to make student record management easy, efficient, and user-friendly. Below is a detailed explanation of each feature:

1. CRUD Operations (Create, Read, Update, Delete)
Create:

Allows administrators to add new student records and Teacher with details such as name, grade, age, and email.
Ensures all necessary fields are filled out before saving the record.
Read:

Displays a tabular list of all students and Teacher in the system.
Provides an overview of essential details like name, grade, and contact information.
Update:

Enables administrators to edit existing student and teacher details.
Updates are reflected instantly in the database.
Delete:

Provides the ability to remove unwanted or outdated student records.
Includes a confirmation prompt to prevent accidental deletions.

3. Responsive Design
The interface is fully responsive and adapts seamlessly to different screen sizes.
Ensures a smooth user experience on devices such as desktops, tablets, and smartphones.
4. Intuitive User Interface
Clean and minimalistic design that prioritizes usability.
Easy navigation for users to manage student data without technical expertise.
Color-coded buttons (e.g., Add, Edit, Delete) for quick identification of actions.
5. Validation and Error Handling
Form Validation:

Ensures mandatory fields are filled when adding or editing records.
Prevents invalid data (e.g., incorrect email formats) from being saved.
Error Messages:

Provides clear error messages for any issues, such as missing fields or invalid inputs.
6. Extendable Architecture
The project is designed with scalability in mind:
Role-Based Access Control (RBAC) can be added to define permissions for administrators, teachers, and other users.
Additional modules, like attendance tracking or report generation, can be integrated easily.
7. Security Features
Implements basic security practices such as:
Validation of user input to prevent invalid data.
Restriction of access to sensitive data via Django's built-in admin panel.
8. Modular Codebase
The project follows Django’s MVC (Model-View-Controller) architecture:
Models: Define the structure of student data in the database.
Views: Handle the business logic for displaying and managing records.
Templates: Render HTML for the user interface.
