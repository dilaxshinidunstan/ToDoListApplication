# ToDoList Application

A simple Android application for managing your tasks. This application allows users to add, view, and delete tasks. Each task includes a name, description, due date, priority, and category.

## Features

- **Add Task**: Add a new task with a name, description, due date, priority, and category.
- **View Tasks**: View all added tasks in a list.
- **Delete Task**: Delete tasks from the list.

## Installation

1. Clone the repository: https://github.com/dilaxshinidunstan/ToDoListApplication.git
2. Open the project in Android Studio.
3. Build and run the application on your Android device or emulator.

## Usage

### Add Task

1. Open the app and navigate to the "Add Task" screen.
2. Fill in the task details:
    - Task Name
    - Description
    - Due Date (Click the field to open the date picker)
    - Priority (Select from the radio buttons)
    - Category (Select from the dropdown)
3. Click the "Add Task" button to save the task.

### View Tasks

1. Navigate to the "View Tasks" screen.
2. All tasks will be listed here.
3. Each task will display the name, description, due date, priority, and category.

### Delete Task

1. Navigate to the "Delete Task" screen.
2. Click the delete button next to the task you want to delete.
3. The task will be removed from the list and the database.

## Code Structure

- **MainActivity.java**: The main entry point of the application.
- **AddActivity.java**: Activity to handle adding new tasks.
- **ViewTasksActivity.java**: Activity to display the list of tasks.
- **DeleteTaskActivity.java**: Activity to delete tasks.
- **TasksAdapter.java**: Adapter to bind task data to the RecyclerView.
- **TaskDbHelper.java**: Helper class to manage database creation and version management.
- **Task.java**: Model class representing a task.

## Database

The application uses SQLite to store tasks. The database schema includes the following fields for each task:
- ID (Primary Key)
- Name
- Description
- Due Date
- Priority
- Category

## Dependencies

- **RecyclerView**: To display the list of tasks.
- **SQLite**: To manage task data storage.

## Contact
For any inquiries, please contact dilaxshini16dunstan@gmail.com. 
