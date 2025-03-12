# To-Do List CLI with Click

This is a simple command-line To-Do List Manager built using Python and the `Click` library. It allows users to add, list, mark as complete, and remove tasks easily using CLI commands.

## Features
- Add new tasks
- List all tasks with completion status
- Mark tasks as completed
- Remove tasks from the list
- Persistent storage using JSON

## Requirements
- Python 3.x
- `click` library

## Installation
Clone the repository and install dependencies:
```sh
git clone https://github.com/ersa-rani/todo-cli.git
cd todo-cli
pip install -r requirements.txt
```

## Usage
Run the script using the following commands:

### Add a Task
```sh
python todo.py add "Buy groceries"
```

### List Tasks
```sh
python todo.py list
```

### Mark a Task as Completed
```sh
python todo.py complete 1
```

### Remove a Task
```sh
python todo.py remove 1
```

## File Storage
The tasks are stored in a JSON file named `todo.json` in the same directory as the script. This ensures persistence across runs.

## License
This project is licensed under the MIT License.

## Contributing
Feel free to submit pull requests or open issues for improvements!

