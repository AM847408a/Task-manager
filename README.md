# Task-manager
# To-Do Manager (Python CLI)

A simple command-line To-Do List manager built in Python. Add, view, complete, and delete tasks — all from your terminal.

This project was built as a beginner-friendly exercise to practice core Python concepts: lists, loops, conditionals, functions, and user input handling.

## Features

- **Add tasks** — save a new task to your list
- **View tasks** — see all current tasks, numbered for easy reference
- **Complete tasks** — mark a task as done without removing it
- **Delete tasks** — remove a task permanently
- **Menu-driven loop** — keeps running until you choose to exit

## How it works

The program stores tasks in a Python list and runs inside a `while True` loop, showing a menu each time:

```
1. Add task
2. Delete task
3. View task
4. Complete task
5. Exit
```

Based on your input, it calls the matching logic:
- Tasks are added with `list.append()`
- Tasks are shown with `enumerate()` so each one has a visible number
- Deleting uses `list.pop(index)`
- Completing a task marks it with a `[DONE]` prefix instead of removing it

## Tech used

- Python 3
- No external libraries — built entirely with Python's standard tools (lists, loops, input/print)

## Getting started

1. Clone this repository:
   ```
   git clone https://github.com/your-username/todo-manager.git
   ```
2. Navigate into the folder:
   ```
   cd todo-manager
   ```
3. Run the program:
   ```
   python todo.py
   ```

## Planned improvements

- Save tasks to a file so they persist between runs (using JSON)
- Add due dates and priority levels
- Build a simple GUI version using Tkinter

## Author

Built by [Your Name] as a learning project.
