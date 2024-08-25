
# Todo_CLI

`Todo_CLI` is a command-line interface (CLI) tool for managing your todo tasks. It allows you to add, list, mark as completed, remove, and update tasks stored in a `todo.json` file.

## Installation

Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/your-username/Todo_CLI.git
cd Todo_CLI
```

Install dependencies (if any):

```bash
npm install
```

## Usage

### Add a New Task

To add a new task to the todo list:

```bash
node todo.js add "Your task description"
```

### List All Tasks

To list all tasks:

```bash
node todo.js ls
```

### Mark a Task as Completed

To mark a specific task as completed:

```bash
node todo.js done <taskNumber>
```

Replace `<taskNumber>` with the number of the task you want to mark as completed.

### Remove a Task

To remove a specific task:

```bash
node todo.js rm <taskNumber>
```

Replace `<taskNumber>` with the number of the task you want to remove.

### Update a Task

To update a specific task:

```bash
node todo.js update <taskNumber> "Updated task description"
```

Replace `<taskNumber>` with the number of the task you want to update and `"Updated task description"` with the new task description.

## Example

```bash
# Add tasks
node todo.js add "Buy groceries"
node todo.js add "Read a book"

# List tasks
node todo.js ls

# Mark the first task as completed
node todo.js done 1

# Update the second task
node todo.js update 2 "Read a novel"

# Remove the first task
node todo.js rm 1

# List tasks again to see the changes
node todo.js ls
```

## License

This project is licensed under the MIT License.
