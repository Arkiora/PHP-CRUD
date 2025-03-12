# PHP CRUD Project
This project is a simple **CRUD (Create, Read, Update, Delete)** application built in PHP. It allows users to manage student records in a database, including adding new students, viewing existing records, updating information, and deleting entries. The project was developed as part of a learning exercise to demonstrate basic web development skills using PHP, MySQL, and HTML. 

## Features
- **Create**: Add new student records with details such as name, date of birth, class, group, gender, email, phone number, and password.

- **Read**: Display all student records in a table format with options to update or delete each entry.

- **Update**: Modify existing student records.

- **Delete**: Remove student records from the database.

- **User-Friendly Interface**: Simple and intuitive forms for adding and updating student information.

## Technologies Used
- **PHP**: Server-side scripting language for handling database operations.

- **MySQL**: Database management system for storing student records.

- **HTML/CSS**: Front-end design for the user interface.

- **Bootstrap**: Used for styling the display table.

## How to Run the Code
1. **Set Up the Environment**:
    - Import the project folder into the `../xampp/htdocs/` directory.
    - Start **XAMPP** and ensure **Apache** and **MySQL** are running.

2. **Create the Database**:
    - Open `localhost/phpmyadmin` in your browser.
    - Create a new database named `CRUD` by running the SQL script provided in `createdb.sql`.

3. **Run the Application**:
    - Open `localhost/PHP-CRUD/display.php` in your browser.
    - You will see the main interface where you can view, add, update, and delete student records.

## Project Structure
- **inscription.php**: The form for adding new student records.

- **display.php**: Displays all student records in a table with options to update or delete.

- **update.php**: Allows users to modify existing student records.

- **delete.php**: Handles the deletion of student records.

- **createdb.sql**: SQL script to create the `CRUD` database and the `eleve` table.

## Example Usage
**Adding a New Student**
- Navigate to `inscription.php`.

- Fill out the form with the student's details and submit it.

- The new student will be added to the database and displayed in the table on `display.php`.

**Updating a Student Record**
- On `display.php`, click the "Modifier" button next to the student you want to update.

- Modify the student's details in the form and submit it.

- The updated information will be reflected in the database and the table.

**Deleting a Student Record**
- On `display.php`, click the "Supprimer" button next to the student you want to delete.

- The student record will be removed from the database and the table.

## About This Project
This project was developed as part of a learning exercise to practice PHP and MySQL. It demonstrates the implementation of basic CRUD operations in a web application, providing a foundation for more complex projects. The project is designed to be simple and easy to understand, making it a great starting point for beginners in web development.