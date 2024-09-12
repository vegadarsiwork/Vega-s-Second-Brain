
---

[[Build your own static website using Gen AI]]

A static website is an application that contains fixed content and displays the same information to every visitor. 
 - It does not have any changing elements (no matter how many times you refresh, the content wont change, unlike Instagram etc.)
 - These websites involve limited user interactions, and each page is primarily developed using HTML and CSS.

---

[[Developing an Application]]

Software development cycle
- Design - Create and define the user interface of the application.
- Develop - Write code based on the design.
- Test - Validate the application's functionality and quality.
- Deploy - Deliver the application to users.

---

[[Introduction to Programming -1]]

case study - when is the best time to post ads? prime time stuffs

operating system - software of softwares
operating system is the mediator between the app you built and the hardware that it is using. main software that helps other softwares communicate with the hardware

interface - face of interaction between 2 parties

code - any set of instructions for a purpose

software - set of instructions given to the hardware (core definition)

soft - easily changeable
ware - functionality

software definition 2 - an easily changeable functionality

updates - modifications to existing things to make it function in a different way

internet - network of networks

---

[[Introduction to Backend]]

Data - any information that has to be stored

Space - size of occupancy on a storage device

Database - makes it easier to access, organize and store data (deal with info)

API - Application Programming Interface

---

[[Introduction to Programming - Python]]

Procedure oriented programming - **a programming model derived from structural programming**. It follows the concept of the calling procedure. The procedures, also called functions, routines, or subroutines, consist of a series of computational steps that they need to carry out. e.g C language

Object oriented programming - **a computer programming model that organizes software design around data, or objects, rather than functions and logic**. An object can be defined as a data field that has unique attributes and behavior. e.g Python, C++, C#, etc.

# Day 2

Variables
Data Types - int, float, string, boolean
Assignment Operator

examples of variable names - Sport, age, height, past participation
examples of values stored -     Cricket, 17, 6'1, Yes
Variables are like containers for storing values.

| Data Type      | Description                                                          |
| -------------- | -------------------------------------------------------------------- |
| Integer (int)  | Any whole number. i.e. 3                                             |
| Float          | Any number including decimals i.e. 3.0, 12.7                         |
| String (str)   | Any text, declared by being wrapped in quotation marks i.e. “Hello!” |
| Boolean (bool) | Only has two possible values, true or false.                         |

Statically typed language - need to assign value to variable with data type mentioned
Dynamically typed language - no need to specify used data type.

---

[[Introduction to Command Line (Linux WSL 2)]]

GUI (Graphical User Interface)**: Visual interface for user interaction.  

CLI (Command Line Interface): Enables powerful operations using text commands.  
Command: Text instruction to perform a specific task.  
Shell: Interprets and executes commands.  
- Examples: Bourne Shell (sh), Bash (bash), C Shell (csh), Korn Shell (ksh), Z Shell (zsh)

Terminal: Text input/output environment.  
File: A collection of related data.  
File Extensions: Indicate the type of file.  
Folders: Containers for storing files.  
Root: The top-level directory (e.g., `C:\`).

### Common Commands:
- **ls -a**: Show directories and files.
- **ls --help**: List all options for `ls`.
- **ls -l -h**: Detailed file info in a readable format.
- **man <command>**: Display manual for a command (`q` to exit).
- **history**: Show command history (default 500).
- **cat**: Display file contents.
- **whoami**: Show the current user.
- **date**: Display system date and time.
- **touch**: Create a file.
- **echo**: Output text in terminal.
  - `echo "text" > file.txt`: Write text to a file.
- **mv**: Rename or move a file.
- **cp**: Copy a file.
- **.**: Current directory.
- **..**: Parent directory.
- **mkdir**: Create a directory.
- **rm -r**: Delete a directory.
- **pwd**: Print working directory.
- **cd**: Change directory.

### File Paths:
- **Absolute Path**: Complete path from the root.
- **Relative Path**: Path relative to the current directory.

---

[[Introduction to Git]]

Version Control: Tracks and manages changes to files over time.

Commit: A snapshot of your project's state at a specific point.

Branch: A separate line of development for new features or fixes.

Merge: Combining changes from one branch into another.

Repository (Repo): A storage space for your project’s files and history.

Clone: Copying an existing repository to your local machine.

Push: Uploading local commits to a remote repository.

Pull: Fetching and merging changes from a remote repository.

Stage: Preparing changes for a commit.

Checkout: Switching to a different branch or commit.