This React ToDo App offers a simple yet elegant solution for efficient task management. It's designed to provide a seamless user experience, with all task data reliably fetched from and persisted to a remote API.

Key Features
This ToDo application boasts a comprehensive set of features to help you stay organized:

Task Management: Easily add, delete, and mark tasks as completed to keep track of your progress.

Flexible Filtering: Quickly navigate your tasks with options to view All, Active, or Completed items.

Data Persistence: Your task data is securely persisted via an external API, ensuring your list is always up-to-date and accessible.

Task Editing: Need to make a change? You can edit existing tasks directly within the application.

Responsive Design: Enjoy a consistent experience across all your devices, as the app features a responsive layout for all screen sizes.

Technologies Under the Hood
The app is built with modern web technologies, ensuring a robust and maintainable codebase:

React: The core JavaScript library for building dynamic user interfaces.

React Router DOM: For seamless navigation and routing within the single-page application.

TypeScript: Enhances code quality and maintainability by adding static typing.

SCSS / CSS Modules / Styled Components: A flexible approach to styling, offering modularity and component-scoped styles.

REST API Integration (using fetch): Handles all communication with the backend for data operations.

Server-side Persistence: Ensures all your changes are saved and available for future sessions.

API Interaction
The application communicates with a single RESTful API endpoint (https://mate.academy/students-api) for all CRUD (Create, Read, Update, Delete) operations related to your tasks.

It's important to note that any client IP address analysis would occur on the server-side at this same endpoint. The client-side application does not directly detect or manage the user's public IP. Instead, the backend API would process and potentially log this information as part of its request handling.

Live Preview
Curious to see it in action?
[👉 View the ToDo List App Online](https://furart.github.io/todolist/)

Getting Started
Ready to run this project locally? Follow these simple steps:

Clone the repository:

git clone https://github.com/FurArt/todolist.git
Navigate to the project directory:

cd todolist

Install dependencies:

npm install

Start the development server:

npm start

Once started, the app will be accessible in your browser at http://localhost:5173.
