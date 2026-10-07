# Todo Application

A simple and user-friendly Todo Application that helps users create, manage, update, and track their daily tasks.

## 📌 Project Overview

The Todo Application allows users to manage their tasks by providing features such as:

- Creating new tasks
- Adding task descriptions
- Setting a due date
- Setting a specific time
- Tracking task status
- Marking tasks as completed/ongoing
- Editing existing tasks
- Deleting tasks
- Clearing the task input form

The application provides a clean interface where all tasks can be viewed and managed from a single page.

## ✨ Features

### Add Task
Users can create a new task by entering:

- Task Title
- Description
- Date
- Time
- Task Status

### View Tasks
All created tasks are displayed in a table with:

| Field | Description |
|---|---|
| ID | Unique task identifier |
| Title | Name of the task |
| Description | Details about the task |
| Date | Task due date |
| Time | Task due time |
| Status | Current task status |
| Actions | Available task operations |

### Update Task Status
Users can toggle the status of a task between its available states, such as:

- `ONGOING`
- `FINISHED`

### Edit Task
Existing tasks can be edited whenever the task details need to be changed.

### Delete Task
Users can permanently remove tasks that are no longer required.

## 🖥️ Application Preview

The application provides a simple dashboard containing a task creation form and a task list.

Example:

- **Complete Java assignment** — Important — 2026-09-22 — 22:00:00 — ONGOING
- **Drink water** — Every morning — 2026-10-07 — 06:00:00 — FINISHED

## 🛠️ Technologies Used

- Java
- Spring Boot
- Maven
- HTML
- CSS
- JavaScript
- REST APIs
- Git & GitHub

## 📂 Project Structure

```text
todo/
├── .mvn/
├── src/
│   ├── main/
│   └── test/
├── .gitattributes
├── .gitignore
├── mvnw
├── mvnw.cmd
└── pom.xml
