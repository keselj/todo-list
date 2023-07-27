# Todo List Project

Welcome to the Todo List project! This project is part of my journey in learning JavaScript from the javascript-full-course-2023 curriculum. The main objective of this project is to create a simple todo list where tasks can be added and removed along with their due dates. Let's dive into the details of the project.

## Project Overview

The project consists of three main files: index.html, todo-list.css, and todo-list.js.

###index.html
This file serves as the user interface for the todo list. It contains the necessary HTML elements to display the todo list and allow users to interact with it. The key components of the HTML file are:

A title "Todo List"
Two input fields for entering the todo name and due date
An "Add" button to add the entered todo to the list
A container to display the list of todos
A link to the todo-list.css stylesheet
A link to the todo-list.js JavaScript file

### todo-list.css

The CSS file provides styling for the todo list user interface. It defines the layout and appearance of the elements on the page. Some of the CSS classes used in the file are:

.todo-grid and .todo-input-grid: These classes define the grid layout for the todo items and input fields.
.name-input and .due-date-input: These classes style the input fields for the todo name and due date.
.add-todo-button and .delete-todo-button: These classes style the "Add" and "Delete" buttons respectively.

### todo-list.js

The JavaScript file contains the functionality of the todo list. It handles adding new todos, rendering the list, and allowing users to delete todos. The main functions in the file are:

renderTodoList(): This function renders the todo list items on the webpage. It iterates through the todoList array and generates HTML elements for each todo, displaying the name, due date, and a "Delete" button.
addTodo(): This function is triggered when the "Add" button is clicked. It retrieves the todo name and due date entered by the user, adds a new todo object to the todoList array, and then calls renderTodoList() to update the display.
Event Listeners: The script sets up an event listener for the "Add" button to call the addTodo() function when clicked. Additionally, event listeners are attached to the "Delete" buttons for each todo item to remove the corresponding todo from the list.

## Getting Started
To run the todo list, simply open the index.html file in a web browser. You will see the "Todo List" interface where you can input new todos with their due dates. Clicking the "Add" button will add the todo to the list, and you can delete any todo by clicking its associated "Delete" button.
