# Pocket Pal

This is a simple web-based Daily Expense Tracking System built using PHP and MySQL. It allows users to track and manage their daily expenses efficiently.

## Installation and Setup

Follow these steps to set up and run the project on your local server:

### 1. Download and Extract  
- Download the ZIP file containing the project.  
- Extract the file and locate the `dets` folder.

### 2. Move the Project Folder  
- Copy the `dets` folder and paste it into your server's root directory:  
  - **XAMPP**: `xampp/htdocs/`  
  - **WAMP**: `wamp/www/`  
  - **LAMP**: `/var/www/html/`

### 3. Set Up the Database  
- Open [PHPMyAdmin](http://localhost/phpmyadmin) in your browser.  
- Create a new database named **`detsdb`**.  
- Import the `detsdb.sql` file from the `sql` folder inside the extracted project.

### 4. Run the Application  
- Open your browser and visit: [http://localhost/dets](http://localhost/dets)

## User Credentials  
You can either register a new user or use the following test credentials:  

- **Username**: `testuser@gmail.com`  
- **Password**: `Test @123`  

## Features  
- Add, edit, and delete daily expenses  
- View expense reports  
- User authentication and session management  

## Technologies Used  
- PHP  
- MySQL  
- HTML, CSS, JavaScript  

---

For any issues or contributions, feel free to submit a pull request or create an issue in this repository.
