Password Manager Application
This is a Python application for managing passwords using a graphical user interface (GUI) built with Tkinter. The application provides functionalities for generating strong passwords, saving them securely, and retrieving them when needed.
Updates in Version 2.0:
This update brings significant improvements to the application's error handling and data storage mechanism. Notable changes include:
* 		Error Handling Enhancement:
    * The application now includes robust error handling mechanisms to ensure smooth operation and to provide user-friendly error messages when necessary.
    * It verifies that essential fields such as website name, email/username, and password are not left empty before saving.
* 		Storage System Migration to JSON File:
    * The previous version of the application utilized a different method for storing password data. In version 2.0, the storage system has been revamped to use JSON files.
    * This migration to JSON offers better organization and readability of the stored data, enhancing the application's scalability and maintainability.
* 		Integration of Boost Library:
    * Boost library has been incorporated to enhance the randomness of password generation. This ensures stronger and more secure passwords for users.
    * The boost library improves the randomness of character selection during password generation, making the generated passwords more robust against potential attacks.
Key Features:
* 		Password Generation:
    * The application provides a secure password generation feature that creates strong passwords consisting of letters (both uppercase and lowercase), numbers, and symbols.
    * Generated passwords are copied to the clipboard for easy usage.
* 		Password Saving:
    * Users can save their passwords securely within the application. Each saved password is associated with a website name, email/username, and password.
    * The data is stored in a JSON file, ensuring persistence across sessions and facilitating easy retrieval.
* 		Password Retrieval:
    * The application allows users to search for passwords by entering the website name. Upon searching, the associated username/email and password are displayed.
Usage:
* 		Generating Passwords:
    * Click the "Generate Password" button to create a strong password. The generated password will be displayed in the designated field and copied to the clipboard automatically.
* 		Saving Passwords:
    * Enter the website name, email/username, and password in the respective fields.
    * Click the "Add" button to save the password securely. Ensure all fields are filled to avoid errors.
* 		Retrieving Passwords:
    * Enter the website name for which you want to retrieve the password.
    * Click the "Search" button to display the associated username/email and password.
How to Run:
* 		Ensure you have Python installed on your system.
* 		Clone or download the repository from GitHub.
* 		Run the Python script (password_manager.py).
* 		The application window will appear, allowing you to utilize its features.
Dependencies:
* Python 3.x
* Tkinter (Python GUI library)
* Pyperclip (Python module for clipboard operations)
* Boost Library



<img width="903" alt="Screenshot 2024-04-11 at 21 38 31" src="https://github.com/HesamFarjad/Password_Generator_Update/assets/81914229/a3d016ca-8234-4e02-a78d-054696c8bc52">

<img width="928" alt="Screenshot 2024-04-11 at 21 38 51" src="https://github.com/HesamFarjad/Password_Generator_Update/assets/81914229/45d6cd64-7c65-47f8-8451-57ba6da25322">

