# To-Do List Application

A simple web-based To-Do List app built with HTML, CSS, and JavaScript to help you organize and manage your daily tasks efficiently.

## Overview

This application allows users to create a list of tasks they want to accomplish. You can add new tasks, mark them as complete, edit existing tasks, and delete tasks when they're no longer needed. The app stores your tasks in the browser’s local storage, so your list remains saved even after you close or refresh the page.

## Features

- **Add tasks:** Quickly add new to-do items.
- **Edit tasks:** Modify task descriptions.
- **Mark tasks complete/incomplete:** Toggle task status.
- **Delete tasks:** Remove tasks you’ve finished or no longer want.
- **Persistent data:** Tasks are saved in your browser using localStorage, so they stay even after refreshing or closing the page.
- **Responsive design:** Works well on desktop and mobile devices.

## How It Works

The app uses simple HTML for the structure, CSS for styling, and JavaScript to handle all interactions and logic:
- When you add a task, JavaScript appends it to the task list in the DOM and saves it in localStorage.
- When you mark a task as complete or delete it, JavaScript updates the list and localStorage accordingly.
- On page load, JavaScript fetches saved tasks from localStorage and displays them.

## How to Use

1. Open the `index.html` file in any modern web browser.
2. Type your task into the input box and press "Add" or hit Enter.
3. Click on a task to mark it complete/incomplete.
4. Use the edit and delete buttons to manage your tasks.

## Technologies Used

- HTML5
- CSS3 (Flexbox/Grid for layout)
- JavaScript (DOM manipulation and localStorage)

## License

This project is licensed under the MIT License.
