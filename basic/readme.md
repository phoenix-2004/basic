Task Management App
This Task Management App is a simple command-line application to help you manage your tasks effectively. The app allows you to add, remove, list, and get recommendations for tasks based on their priority.

Features
Add Task: Add a new task with a description and priority (Low, Medium, High).
Remove Task: Remove an existing task by its description.
List Tasks: List all the tasks along with their priorities.
Recommend Task: Get a recommendation for a high-priority task.
Installation
To get started with the Task Management App, follow these steps:

Clone the repository:

git clone https://github.com/yourusername/task-management-app.git
Navigate to the project directory:

cd task-management-app
Install the required Python packages:

pip install pandas scikit-learn
Usage
To run the Task Management App, use the following command:

python task_management_app.py
Once the app is running, you will see a menu with the following options:

Add Task: Enter the task description and priority.
Remove Task: Enter the task description to remove it from the list.
List Tasks: View all the tasks along with their priorities.
Recommend Task: Get a recommendation for a high-priority task.
Exit: Exit the application.
Data Persistence
The tasks are saved to a CSV file (tasks.csv) in the same directory as the script. When the app is launched, it will load any pre-existing tasks from this file.

Example

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