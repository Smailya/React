# Simple Todo Application

## Overview

This project is a straightforward yet effective **Todo application** that allows users to add and remove tasks. While foundational, it covers essential CRUD (Create, Read, Update, Delete) operations, state management, and user interaction-core concepts that underpin most modern applications.

## Why This Matters

For full-stack engineers, mastering these fundamentals is critical. This project helped me deepen my understanding of:

- React hooks for managing component state  
- Local state management  
- Form handling and validation  
- Designing clean and intuitive user interfaces  

These skills enable the development of efficient, user-friendly interfaces that support everyday business workflows and boost productivity.

## Technologies Used

- React  
- JavaScript  

## Features

- Add new tasks to the todo list  
- Remove completed or unwanted tasks  
- Real-time UI updates reflecting user actions  
- Simple and clean user interface  

## Getting Started

### Prerequisites

- Node.js and npm installed  
- Basic knowledge of React  

### Installation

1. Clone the repository:

git clone https://github.com/yourusername/simple-todo-app.git

text

2. Navigate to the project directory:

cd simple-todo-app

text

3. Install dependencies:

npm install

text

4. Start the development server:

npm start

text

5. Open your browser and visit `http://localhost:3000` to use the app.

## Usage

- Enter a task description in the input field and press "Add" to create a new task.  
- Click the "Remove" button next to a task to delete it from the list.  

## Example

const [tasks, setTasks] = useState([]);

const addTask = (task) => {
setTasks([...tasks, task]);
};

const removeTask = (index) => {
setTasks(tasks.filter((_, i) => i !== index));
};

text

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License.

---
Developed by Ismail Cisse 
Building foundational React applications that power efficient and user-friendly interfaces.
