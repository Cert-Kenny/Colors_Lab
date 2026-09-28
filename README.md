
# COLORS — LAMP Stack Web Application

## Project Description
COLORS is a web application developed for COP4331. It allows users to log in, add colors to their account, and search for previously saved colors. The application uses a remote server and MySQL database to store user information and colors.

## Technologies
- HTML and CSS for the user interface
- JavaScript and AJAX for communication with the backend
- PHP for backend API endpoints
- MySQL for database storage
- Apache and Ubuntu for web hosting
- DigitalOcean for deployment

## Project Structure
- `index.html` — Login page
- `color.html` — Color management page
- `css/` — Stylesheets
- `js/` — Frontend JavaScript
- `images/` — Website images
- `LAMPAPI/` — PHP API endpoints

## Setup Instructions
1. Set up a LAMP server with Apache, PHP and MySQL.
2. Create a MySQL database and the required Users and Colors tables.
3. Create `LAMPAPI/config.php` with your own database credentials.
4. Upload the frontend files to the Apache web directory.
5. Upload the PHP endpoints and private configuration file to `LAMPAPI/`.
6. Update `js/code.js` so its API base URL points to the deployed PHP directory.

## Running the Application
Open the deployed website in a browser. Log in using an account in the database, add a color, and search for saved colors.

## Live Website
http://notworthmoney.shop

## Limitations
- Users must have an existing account; public registration is not provided.

## AI Usage
ChatGPT was used to assist intructions on how to upload to github, explaining LAMP configuration, debugging deployment issues.
