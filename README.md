# Cointab-Assignment

This application is a web-based system designed to manage user information and posts. It includes both frontend and backend components. The backend is developed with Node.js and Express, while the frontend is built using HTML, CSS, and JavaScript. MySQL database is utilized to store user and post data.

![image](https://github.com/chaitanya140/Cointab-Assignment/blob/main/Cointab%20Assignment.png)

# Project Type:

Fullstack

# deployed links :

frontend : <a href="#">Cointab Assignment Frontend</a>

Backend : <a href="#">Cointab Assignment Backend</a>

# Features:

- User get and post request: Allows users to be retrieved from an external API and added to a local database.
- Post get and post(Bulk add) request: Enables users to view posts retrieved from an external API, add them to the local database, and download them in Excel format.
- Database Interaction and cloud servies(aiven): Utilizes MySQL database for storing user and post data.
- API Integration: Communicates with external APIs to fetch user and post data.

# Backend:

# Technologies Used:

- Node.js: JavaScript runtime for server-side development.
- Express: Web application framework for Node.js.
- MySQL: Relational database management system.

# Backend Structure:

- index.js: Main entry point for the backend application. Sets up the Express server and defines routes.
- /db.js: Configuration file for establishing a connection with the MySQL database.
- Routes/user.routes.js: Defines routes for user-related functionalities such as fetching and adding users.
- Routes/posts.routes.js: Defines routes for post-related functionalities such as fetching and adding posts.

# Frontend:

# Technologies Used:

- HTML
- CSS
- JavaScript


# Setup Instructions:

1. Clone the Repository: git clone https://github.com/chaitanya140/Cointab-Assignment
2. Install Dependencies: cd backend && npm install
3. create env file with related mongodb credintials.
4. Database Configuration:
   - Set up a MySQL database and configure credentials in backend/db.js.
5. Run the Application:
   - Backend: cd backend && npm run server
