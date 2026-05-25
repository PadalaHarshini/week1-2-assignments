# TODO-APP

A modular, console-based JavaScript application to manage daily tasks. This application demonstrates clean code separation by isolating the core application logic, task structures, and input validation into dedicated modules.

---

##  Project Structure

The project is divided into three primary files:

* **`task.js`**: Defines the blueprint/structure for a Task object (e.g., properties like `id`, `title`, `description`, and `status`).
* **`validator.js`**: Contains helper functions to validate user inputs, ensuring tasks aren't created with empty names or invalid states.
* **`app.js`**: The main entry point of the application that manages the orchestration, state tracking, and user interactions.

---

## Features

* **Create Tasks:** Add new to-do items with unique identifiers.
* **Read/List Tasks:** View a clean layout of all pending and completed activities.
* **Input Validation:** Built-in validation system to catch empty strings, null values, or formatting errors before processing data.
* **State Management:** Track task transitions cleanly across your runtime.

---

##  Getting Started

### Prerequisites
Make sure you have [Node.js](https://nodejs.org/) installed on your machine.

### Running the Application

1. Clone or navigate to your local repository folder:
   ```bash
   cd week2/TODO-APP
