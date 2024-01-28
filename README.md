# TaskManager
Muhammad Salman_0384610 Task Manager App(SoftDev_Task02)

This is a Software Development with Python (Master of Computer Science) assignment
where I created a task manager console application using Python.

Abstract:
Command Line Task Manager is a Python-based application that provides a  streamlined
and efficient solution for task management in a command line interface.
The main goal is to provide users with easy and powerful tools to seamlessly organize and prioritize tasks.

Purpose:
In a fast-paced digital environment, effective task management is critical to productivity.
Command Line Task Manager addresses this need by providing a command line interface that eliminates
the clutter of graphical interfaces and provides a  distraction-free environment where users can focus and manage their tasks.

Key Features:

1. Task Creation:
- Users can easily add tasks to the system using simple commands that specify task details
such as title, description, and deadline.

2. Task Deletion:
- This application allows users to delete completed or no longer needed tasks to ensure an organized to-do list.

3. Task Listing:
- Comprehensive to-do list functionality allows users to see all their tasks at a glance.
 Tasks are displayed with relevant details, facilitating quick evaluation.

4. Status Updates:
- Users can update the status of tasks to indicate whether the task is pending, in progress, or  completed.
 This feature provides greater visibility into task progress.

5. Interactive Interface:
- The application offers an interactive and user-friendly interface, guiding users through
various functionalities with clear prompts and instructions.

6. Data Persistence:
- Task data is persistently saved, so users can close and reopen the application without losing  task information.

7. Customization Options: (Not made yet)
- This application allows users to customize their experience by adjusting settings such as B.
 Default view or sort settings.

8. Deadline Tracking:
- The application includes deadline functionality, helping users stay on top of deadlines and
manage their time effectively.

9. User-Friendly Commands:
- Commands are designed to be intuitive and easy to remember, reducing the learning curve for users new
to command line interfaces.

Benefits:
- Focus and Productivity:
The application's minimalist design fosters focus, allowing users to concentrate on task
management without unnecessary distractions.

- Educational Tool:
The command line task manager serves as an educational tool for those who want to improve their Python programming skills.
The codebase is accessible and encourages exploration  and learning.

- Integration Possibilities:
Due to its command-line nature, the application can be easily integrated into scripts and automated processes,
extending its usefulness beyond standalone task management.

- Efficient Task Tracking:
The combination of priority management, due date tracking, and status updates provides users with
a comprehensive system for efficiently tracking and completing tasks.
In summary, command-line task manager applications provide a convenient and feature-rich solution for
users looking for an effective and targeted way to manage tasks  in a command-line environment.
Its design emphasizes ease of use, customization, and educational benefits, making it suitable for both
those who value productivity  and those looking to  improve their  Python programming skills.


# How to Run Task Manager Application

Task Manager CLI Documentation:
- This document provides instructions for running and using the Task Manager command line interface (CLI).
  This program allows users to manage tasks by adding, viewing, updating, deleting, and changing their status.

Prerequisites:
- Before running the program, ensure that you have the required dependencies installed. You can install the 
  necessary packages using the following command:
- pip install rich

Running the Program:
- Clone the repository containing the Task Manager CLI program.
git clone (https://github.com/itxmsalman/TaskManager.git)
cd task-manager

Run the Program:
- Run the program by issuing the following command: 
- python task_manager.py
The program will start, by presenting a menu of options for managing tasks.

Options List:
(Option 01) Add a Task:

Enter "1" to add a new task.
Provide the task name, task information, deadline, and status when prompted.
The task will be added to the task list in the database.

(Option 02) Show all Tasks:
Enter "2" to view all tasks.
The program will display a table showing the task name, description, deadline, and status for each task.

(Option 03) Remove a Task:
Enter "3" to remove a task.
The program will display a list of tasks, and you will be prompted to enter the task name to be deleted.
The specified task will be removed from the task list.

(Option 04) Modify a Task:
Enter "4" to modify a task.
Select the task from the list and provide the new task name.
The specified task will be updated with the new name.

(Option 05) Modify Status:
Enter "5" to modify the status of a task.
Choose the task from the list and provide the new status.
The status of the selected task will be updated.

(Option 06) Exit:
Enter "6" to exit the program.

Important Notes:
- The program uses a JSON file "db.json". Permanently save task information.
- Make sure the file is in the same directory as your program.
- Follow the on-screen instructions and enter the required information accurately.
- Using an invalid option results in an "Invalid Option" message.

Example Usage
- python task_manager.py

Follow the on-screen instructions to manage tasks efficiently using the Task Manager CLI.

Note: Adjust file paths and dependencies accordingly based on your project structure and environment.
