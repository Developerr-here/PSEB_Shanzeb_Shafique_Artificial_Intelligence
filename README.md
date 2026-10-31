Task Tracker Mini Project

Project Goal

The goal of this project is to build a menu-based Python application that tracks tasks. It allows users to manage a simple to-do list that persists across different sessions by storing and reloading the task data using a JSON file (tasks.json).

Features

Add Tasks: Create new tasks, which are automatically stored with a "Pending" status.

View Tasks: Display a numbered list of all tasks alongside their current status (Pending or Done).

Complete Tasks: Select a task by its number and update its status to "Done".

Delete Tasks: Select a task by its number and permanently remove it from the list.

Persistent Storage: Automatically saves the task list to tasks.json after any modification and loads it when the program starts.

Error Handling: Gracefully handles empty task titles, invalid menu choices, invalid task numbers, and missing JSON files.

How to Run the Program

In Google Colab (Recommended for this project)

Copy the Python code provided into a new code cell in your Google Colab notebook.

Click the "Run" button (the play icon) on the left side of the cell.

The interactive menu will appear below the cell. Type your choices (1-5) into the prompt and press Enter to interact with the tracker.

Note: The tasks.json file will be saved in the temporary files of your Colab runtime. It will persist as long as the runtime is active.

Locally on your computer

Ensure you have Python installed on your computer.

Save the provided Python code in a file named mini_task_tracker.py.

Open your terminal or command prompt.

Navigate to the folder where you saved the file.

open file in vscode, it'll ask you to install jupyter extension if you don't have already and then run the code cell.

Follow the on-screen menu to manage your tasks.
