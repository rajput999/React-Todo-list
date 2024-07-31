# Todo List Application

## Overview

This project is a frontend Todo List application built using Reacts. The application allows users to create, update, mark as done, and search tasks. The tasks are displayed in an expandable list format, showing a description and a timestamp of the last update when expanded. 

## Features

- **Create Task:** Users can add new tasks.
- **Update Task:** Users can edit existing tasks.
- **Mark as Done:** Users can mark tasks as completed.
- **Search Tasks:** Users can search and filter tasks.
- **Expandable List:** Tasks are displayed in an expandable list format with descriptions and timestamps.

## System Design

The application follows a modular design with the following components:

1. **TaskForm:** Handles task creation and updates.
2. **TaskList:** Displays the list of tasks.
3. **TaskItem:** Represents a single task in the list.
4. **SearchBar:** Allows users to search and filter tasks.
5. **ExpandableTask:** Displays expanded task details.

## Implementation

### Creating and Updating Tasks

- The `TaskForm` component handles both task creation and updating.
- Form data is managed using controlled components in React.

### Marking Tasks as Done

- Each task has a "Done" button that updates its status.
- Task status is visually indicated by striking through the task text.

### Searching Tasks

- The `SearchBar` component handles user input for searching tasks.
- URL parameters are used to manage and persist search queries across reloads.

### Expandable List

- The `TaskItem` component displays a brief view of each task.
- Clicking on a task expands it to show additional details such as the description and last update timestamp.


## Setup and Run

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/todo-list-app.git
   cd todo-list-app
2. Install dependencies:
   npm install
   # or
   yarn install

### Running the Application

1. Start the development server:
   npm start
2. Open the application in your browser:
   http://localhost:3000