# Todo App


This is a simple Todo App built with React.js, Tailwind CSS, Context API, and Local Storage. It allows users to create, read, update, and delete tasks, providing an organized way to manage their daily tasks. The use of Local Storage ensures that your tasks are persisted even after you close and reopen the application.

## Features

- Add new tasks to your to-do list.
- Mark tasks as completed or uncompleted.
- Edit task names.
- Delete tasks you no longer need.
- Clear all completed tasks in one click.
- Responsive design for a seamless experience on various screen sizes.

## Technologies Used

- **React.js:** The frontend of the application is built using React.js, a popular JavaScript library for building user interfaces.

- **Tailwind CSS:** Tailwind CSS is used for styling the application. It is a utility-first CSS framework that allows for rapid development and customization.

- **Context API:** The Context API is used to manage the state of the application, ie the task and its respected functions like add, update, delete and taskCompletechecking. It provides a way to share data between components without having to pass props manually.

## Getting Started

To get started with this project, follow these steps:

1. **Clone the Repository:**
   ```
   git clone https://github.com/Sayakdutt/Todo-React.git
   ```

2. **Navigate to the Project Directory:**
   ```
   cd Todo-React
   ```

3. **Install Dependencies:**
   ```
   npm install
   ```

4. **Start the Development Server:**
   ```
   npm run dev
   ```

   This will start the development server, and the app will be accessible at `http://localhost:5173`.

## Usage

- To add a new task, enter a task description in the input field at the top of the app and press the "Enter" key.

- To mark a task as completed or uncompleted, click on the checkbox next to the task.

- To edit a task name, double-click on the task text, make your changes, and press the "Enter" key to save.

- To delete a task, click the "X" icon next to the task.

- Your tasks are automatically saved in Local Storage, so they will be there even if you close and reopen the app.



## Acknowledgments

- This project was created as a learning exercise and is inspired by various tutorials and examples in the React.js and Tailwind CSS communities.

