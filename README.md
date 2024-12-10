# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

# Kanban Board Application

This Kanban board application allows users to manage tasks across different stages: To Do, In Progress, Peer Review, and Done. The board supports drag-and-drop functionality for task movement and includes a search box to filter tasks by title.

## Features

- **Kanban Board Layout**: Four sections/columns representing task stages:
  - To Do
  - In Progress
  - Peer Review
  - Done

- **Task Cards**: Each task card displays:

  - Task Title
  - Task Description
  - Tasks are draggable between columns.

- **Drag and Drop Functionality**: Move tasks between columns and place them in the correct position.
- **Search Functionality**: Filter tasks in all columns based on the search input.
- **Add New Tasks**: Create new tasks in the To Do column.
- **Responsive Design**: The UI is fully responsive.
- **State Management**: Uses Redux for state management.
- **Styling**: Uses Material-UI for styling.

## Technologies Used

- ReactJS
- Redux
- React-DnD (for drag-and-drop functionality)
- Material-UI (for styling)
- Local Storage (for data persistence)
