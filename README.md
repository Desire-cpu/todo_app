# ToDo Website

This is a simple to-do website that allows users to add tasks and remove them. It utilizes a PostgreSQL database to store the tasks.

## Features

- Add tasks: Users can add tasks to their to-do list.
- Remove tasks: Users can remove tasks from their to-do list.
- Persistence: Tasks are stored in a PostgreSQL database, ensuring that they are saved even if the user closes the browser.

## Technologies Used

- HTML: Markup language used for creating the structure of web pages.
- CSS: Styling language used for styling the web pages and making them visually appealing.
- JavaScript: Programming language used for adding interactivity and functionality to the website.
- Node.js: JavaScript runtime environment used for running server-side code.
- Express.js: Web application framework for Node.js used for building web applications and APIs.
- PostgreSQL: Relational database used for storing task data.
- Sequelize: ORM (Object-Relational Mapping) library for Node.js used for interacting with the PostgreSQL database.
- EJS (Embedded JavaScript): Templating language used for generating HTML markup dynamically on the server-side.

## Prerequisites

Before running the application, ensure that you have the following installed on your system:

- Node.js: Download and install Node.js from https://nodejs.org/
- PostgreSQL: Download and install PostgreSQL from https://www.postgresql.org/

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/todo-website.git
Navigate to the project directory:

bash
Copy code
cd todo-website
Install dependencies:

bash
Copy code
npm install
Set up the PostgreSQL database:

Create a new PostgreSQL database.
Update the database configuration in the config/config.json file with your database credentials.
Run database migrations to create the necessary tables:

bash
Copy code
npx sequelize-cli db:migrate
Start the server:

bash
Copy code
npm start
Open your web browser and navigate to http://localhost:3000 to access the application.

Usage
Add a Task:

Click on the "Add Task" button.
Enter the task details and click "Submit".
Remove a Task:

Click on the "Remove" button next to the task you want to remove.
Contributing
Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.