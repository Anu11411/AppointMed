# AppointMed
Developed using HTML5, CSS3, JavaScript, PHP 5.0+,AJAX ,MySql.

# Overview
The Doctor Appointment System is a web application designed to help users schedule appointments with doctors. It is a comprehensive project that involves multiple technologies and provides a real-world application scenario.

# Technologies Used
- *PHP*: Handles server-side logic and interactions with the database.
- *MySQL*: Stores appointment data and user information.
- *HTML/CSS*: Structures and styles the web pages.
- *JavaScript*: Adds interactivity to the application.
- *AJAX*: Allows for asynchronous updates without reloading the page.
- *Bootstrap*: Used for responsive and aesthetically pleasing UI design.

# Project Structure
- *Backend/*: Contains PHP scripts for handling database interactions and business logic.
- *Frontend/*: Includes HTML, CSS, and JavaScript files for the user interface.
- *database_con.php*: Database connection script.
- *index.php*: Main entry point for the application.
- *login.php*: Handles user authentication.
- *admin.php*: Admin dashboard for managing appointments.
- *appointment.php*: Interface for users to schedule appointments.

# How It Works
1. *User Registration and Login*: Users register and log in through login.php. The credentials are verified against the database.
2. *Scheduling Appointments*: Users navigate to appointment.php to schedule an appointment. The form data is submitted via AJAX to avoid page reloads, enhancing user experience.
3. *Database Operations*: All appointment data is stored in a MySQL database. PHP scripts in the Backend folder handle the creation, reading, updating, and deletion of appointment records.
4. *Admin Interface*: The admin.php file provides an interface for administrators to view and manage all appointments. This includes updating and deleting records as needed.
5. *Real-time Updates*: AJAX is used to update the appointment list in real-time without requiring a full page refresh, ensuring a smooth and responsive user experience.
