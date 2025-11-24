Console To-Do List Application

A simple, console-based To-Do List application written in Python 📅. This tool helps you manage your tasks, set due dates, mark items as complete, and ensures your data is saved persistently between sessions.

This project is excellent for B.Tech first-year students to practice fundamental Python concepts like functions, control flow, file I/O using JSON, and basic date manipulation.

🛠️ Requirements

Python 3.6+ (No external libraries are required; it uses standard built-in modules only.)

🚀 How to Run

Save the Code: Save the Python code into a file named todo_app.py.

Run from Terminal/Command Prompt: Navigate to the directory where you saved the file and execute the script:

python todo_app.py


📝 Features

The application presents a simple menu with the following options:

Add Task: Prompts you for a due date (YYYY-MM-DD format) and a task description, then saves it.

View Tasks: Displays all current tasks, sorted by their due date. Completed tasks are marked with a ✓.

Mark Task Complete: Allows you to select a task number to toggle its completion status.

Delete Task: Allows you to select a task number to permanently remove it from the list.

Exit: Closes the application.

💾 Data Persistence

All your tasks are automatically saved to a file named tasks.json in the same directory as the script. You do not need to manually interact with this file; the application handles loading and saving the data automatically.

