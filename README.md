# Task-Manager

Task Manager

Task Manager is a web-based application that allows users to manage their tasks and to-do lists. It provides features to add, edit, and delete tasks, set deadlines, mark tasks as completed, and more.

Features

	•	User Authentication: Users can register and log in securely to access their personalized task lists.
	•	Dashboard: Users can view their tasks and to-do lists on the dashboard, sorted by priority or due date.
	•	Add and Edit Tasks: Users can add new tasks with details like task name, description, deadline, and priority. They can also edit and update existing tasks.
	•	Mark Tasks as Completed: Users can mark tasks as completed, and completed tasks are moved to a separate “Completed Tasks” section.
	•	Search and Filter: Users can search for specific tasks and apply filters based on task attributes like priority or due date.
	•	Reminders: Users can set reminders for upcoming tasks and receive notifications via email or push notifications.

Tech Stack

	•	Frontend: HTML, CSS, JavaScript (Vue.js)
	•	Backend: Node.js with Express
	•	Database: MongoDB
	•	User Authentication: JWT (JSON Web Tokens)

Installation

	1.	Clone the repository:

git clone https://github.com/your-username/task-manager.git
cd task-manager

	2.	Install dependencies for the frontend and backend:

cd frontend
npm install

cd ../backend
npm install

	3.	Set up environment variables:
Create a .env file in the backend directory with the following variables:

PORT=3000
MONGODB_URI=mongodb://localhost:27017/taskmanager
JWT_SECRET=your_jwt_secret_here


	4.	Run the application:

# Start the backend server
cd backend
npm start

# Start the frontend development server
cd frontend
npm run serve

	5.	Open your web browser and visit http://localhost:8080 to access the application.

Usage

	•	Register a new account or log in with an existing account to access the dashboard.
	•	Add new tasks by clicking on the “Add Task” button and filling in the required details.
	•	Edit tasks by clicking on the “Edit” button next to each task.
	•	Mark tasks as completed by clicking on the checkbox next to each task.
	•	Use the search bar and filters to find specific tasks based on priority or due date.

Contribution

If you find any bugs or have suggestions for improvement, feel free to open an issue or submit a pull request. Contributions are welcome!

License

This project is licensed under the MIT License - see the LICENSE file for details.
