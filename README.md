# To-Do List App (Unreal Engine 5)

A to-do list “app-style” UI project built in Unreal Engine 5 using UMG for the interface and Blueprints for all functionality. It supports creating tasks with priority and optional due dates, viewing them in a list, marking tasks complete, deleting tasks, and filtering by priority.

View Demo Video-https://youtu.be/aA1XqaND2fg?si=GKtfnL1odLYiJf5C

## Screenshots

- Main UI:<img width="2560" height="1383" alt="Mainappinterface" src="https://github.com/user-attachments/assets/ecf01fe5-6b7e-4322-9ba9-15021ad78a85" />

- Task creation flow:![TaskCreationFlow](https://github.com/user-attachments/assets/78f0c341-b9bc-43fe-a88a-d1ff1b992371)

- Task list view:![Tasklistview](https://github.com/user-attachments/assets/22fa852a-a03f-40fe-8315-ed1bda692598)

- Completed tasks:![Completedtasks](https://github.com/user-attachments/assets/2bab24c9-8c03-481a-85a5-acb1b506876a)

- Editing: ![TaskEditing](https://github.com/user-attachments/assets/f2f33be9-c334-421f-99f0-e89168da9be6)

- UI polish:![Uipolish](https://github.com/user-attachments/assets/d3791113-7e6f-44c2-9205-2bc2138b5607)

## Features

- Create tasks from a text input with an **Add Task** button
- Assign task priority: High / Medium / Low
- (Optional) Set a due date for each task
- View tasks in a scrollable list with per-task rows
- Mark tasks as completed using a checkbox
- Delete individual tasks with a delete/trash button
- Filter tasks by priority: Show All, High, Medium, Low
- Clear all tasks with one click
- Exit button from the main UI

---

## Tech Stack

- Unreal Engine 5
- UMG (Unreal Motion Graphics) for UI
- Blueprints (visual scripting) for logic and UI event handling

---

## How to Use

1. Type a task name in the input field (“Enter New Task Here…”).
2. (Optional) Enter a due date.
3. Choose a priority (High / Medium / Low).
4. Click **Add Task** to add it to the list.
5. Use:
   - The checkbox to mark complete
   - The trash icon to delete a task
   - The Filter buttons to show specific priorities
6. Use **Clear All Tasks** to reset the list, or **Exit App** to close.
