# Task Management CLI Tool
This is a command-line tool for managing your to-do tasks. You can use it to add, view, complete, and delete tasks. The tasks are stored in a file called tasks.txt, so they will be saved between sessions.

#How to Use
1. Add a Task
To add a task, use the add command followed by the task description.
Example:
python task_manager.py add "Buy groceries"

2. View Tasks
To see all your pending tasks, use the list command.
Example:
python task_manager.py list

3. Complete a Task
To mark a task as completed, use the complete command followed by the task number.
Example:
python task_manager.py complete 1

4. Delete a Task
To delete a task, use the delete command followed by the task number.
Example:
python task_manager.py delete 1

#File Used
The tool saves your tasks in a file called tasks.txt so that they remain even when you close the program. Make sure this file is in the same directory as the 



#Summary of the Design:
Storage: Tasks are stored in a text file (tasks.txt).
Core Functions: Simple functions handle specific operations (adding, listing, completing, deleting tasks).
CLI Interaction: Users interact with the tool by providing commands via the command line.
Task Persistence: The tasks remain stored in the text file between different program runs, so they are not lost after the program ends.script.
