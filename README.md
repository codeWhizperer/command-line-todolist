# Rust Task Manager

This is a simple command-line task manager implemented in Rust, which allows you to add, complete, list and remove tasks.

# Installation 

Install Rust by following the instructions on the official Rust website.
Clone this repository by running git clone https://github.com/codeWhizperer/command-line-todolist in your terminal.
Change to the project directory by running cd command-line-todolist.
Run cargo build --release to build the project in release mode.
Usage
Once the project is built, you can run the executable file target/release/task-manager from the command line. Here are the available commands:

- add "task text": adds a new task with the given text.
- complete task_id: completes the task with the given ID.
- list: lists all the tasks.
- remove task_id: removes the task with the given ID.

# For example:
- To add a new task, run cargo run -- -j test-journal.json add `task` 
- To complete the task with ID 1, run cargo run -- -j test-journal.json done 1
- To list all tasks, run cargo run -- -j test-journal.json list 
- To remove the task with ID 1, run cargo run -- -j test-journal.json remove-task 1
- To list a task with ID 1, run cargo run -- -j test-journal.json list-task 1

Contributing
If you find a bug or have a suggestion for a new feature, feel free to open an issue or submit a pull request. Before contributing, please read the code of conduct.


