# Simple Python Console To-Do List Application

This is a basic command-line interface (CLI) application that allows users to manage their to-do tasks. Tasks are stored persistently in a text file, so they remain even after the application is closed.

## Features

* **Add Tasks:** Users can add new tasks to their to-do list.
* **View Tasks:** Displays all current tasks with sequential numbering.
* **Remove Tasks:** Allows users to remove tasks by their number.
* **Persistence:** All tasks are saved to a `todo.txt` file, ensuring data is retained between sessions.
* **User-Friendly Interface:** Menu-driven interaction for easy navigation.
* **Input Validation:** Basic handling for non-numeric input when removing tasks.

## Technologies Used

* Python 3

## How to Run

1.  **Clone the repository (or download the `todo.py` file):**
    ```bash
    git clone YOUR_TODO_REPO_URL_HERE
    cd YOUR_TODO_REPO_FOLDER
    ```
    *(Replace `YOUR_TODO_REPO_URL_HERE` with the actual URL of your To-Do List GitHub repository, e.g., `https://github.com/codebyte09/python-todo-list`.)*
    *(If you just downloaded `todo.py`, navigate to its directory in your terminal.)*

2.  **Run the script:**
    ```bash
    python todo.py
    ```
    *If `python` doesn't work, try `python3`.*

## Usage

When you run the script, you will see the main menu:
--- To-Do List Application ---

View tasks
Add task
Remove task
Exit
Enter your choice (1-4):

* **1. View tasks:** Shows all tasks currently in your list.
* **2. Add task:** Prompts you to enter a new task.
* **3. Remove task:** Displays tasks and asks you to enter the number of the task you wish to remove.
* **4. Exit:** Closes the application. Your tasks will be saved.
