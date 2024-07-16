# Task Management App

This Task Management App is a simple command-line application designed to help you manage your tasks effectively. The app allows you to add, remove, list, and get recommendations for tasks based on their priority.

## Features

- **Add Task**: Add a new task with a description and priority (Low, Medium, High).
- **Remove Task**: Remove an existing task by its description.
- **List Tasks**: List all the tasks along with their priorities.
- **Recommend Task**: Get a recommendation for a high-priority task.

## Installation

To get started with the Task Management App, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/task-management-app.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd task-management-app
   ```

3. **Install the required Python packages:**
   ```bash
   pip install pandas scikit-learn
   ```

## Usage

To run the Task Management App, use the following command:

```bash
python task_management_app.py
```

Once the app is running, you will see a menu with the following options:

1. **Add Task**: Enter the task description and priority.
2. **Remove Task**: Enter the task description to remove it from the list.
3. **List Tasks**: View all the tasks along with their priorities.
4. **Recommend Task**: Get a recommendation for a high-priority task.
5. **Exit**: Exit the application.

### Adding a Task

To add a task, select option `1` from the menu. You will be prompted to enter a task description and priority (Low, Medium, or High). The task will be saved to the `tasks.csv` file and added to the list of tasks.

Example:
```text
Select an option: 1
Enter task description: Finish report
Enter task priority (Low/Medium/High): High
Task added successfully.
```

### Removing a Task

To remove a task, select option `2` from the menu. You will be prompted to enter the task description of the task you want to remove. The task will be removed from the `tasks.csv` file.

Example:
```text
Select an option: 2
Enter task description to remove: Finish report
Task removed successfully.
```

### Listing Tasks

To list all tasks, select option `3` from the menu. The tasks along with their priorities will be displayed.

Example:
```text
Select an option: 3
         description priority
0    Finish report      High
```

### Recommending a Task

To get a task recommendation, select option `4` from the menu. The app will recommend a high-priority task if available.

Example:
```text
Select an option: 4
Recommended task: Finish report - Priority: High
```

### Exiting the Application

To exit the application, select option `5` from the menu. The app will close, and any unsaved changes will be lost.

## Data Persistence

The tasks are saved to a CSV file (`tasks.csv`) in the same directory as the script. When the app is launched, it will load any pre-existing tasks from this file.

## Example Session

```text
Task Management App
1. Add Task
2. Remove Task
3. List Tasks
4. Recommend Task
5. Exit

Select an option: 1
Enter task description: Finish report
Enter task priority (Low/Medium/High): High
Task added successfully.

Select an option: 3
         description priority
0    Finish report      High

Select an option: 4
Recommended task: Finish report - Priority: High
```
