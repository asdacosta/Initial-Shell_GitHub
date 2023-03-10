# Shell & GitHub 
## Project Origin
Personal project.

## Project Objective
Aims to learn about everything in GitHub and Shell. It entails terms and commands used regularly.

## Project Relevance
The project made me grasp the fundamentals and concepts in GitHub and Shell. I practiced with each command via mini projects to solidify all that I learnt.

## Intended Audience
Developers, users, and recruiters.

## Technologies
* `Ubuntu` in Terminal
* `VS Code`
* `Vi` text editor

## How To Get Started (Developers & Users)
Users should go through the notes, `git_notes` and `shell_notes`, to grasp the concepts before tackling the practical aspect: creating each script in `linux_shell` directory that performs the respective function as shown in the table below.
### How To Test Code
Make script executable:
~~~
chmod +x script_name
~~~
To run script in command line:
~~~
./script_name [Option (If there should be)]
~~~

## Files In `linux_shell` Directory
The following are executable shell scripts. 

| Script | Functions |
| -------- | ----------- |
| `0-echo` | Echo two sentences on two different lines on the console. |
| `1-echo` | Echo files and directories ending with the string .txt on the console without a new line. |
| `3-man [Command]` | Display brief description of any shell command. |
|  `4-list_previous` | List all files and directories in parent directory of the current working directory. |
| `5-dir [Permission] [Directory name]` | Create a directory with any specified name `Directory name` and permission for only the owner `Permission`. |
| `6-create_with_name [Name]` | Create a script that when executed, displays an intro to the name `Name`. |
| `intro` | Script created from executing the above script, which displays text with name that was specified earlier `Name`. |
| `7-give_perm [Permission] [File name]` | Change the permission of a any file name and echo the changes made. |
| `8-top_bottom [File name]` | Display first three lines and last four lines of `File name`. |
| `9-how_many [Text] [File name]` | Display the number of lines containing the string `Text` in the file `File name`, including the string with uppercase and lowercase letters. |


## Shell Command
The following are the functions of some shell or linux commands.

| Command | Function |
| ------- | -------- | 
| `man` | Displays manual page or documentation of commands. |
| `ls` | List files and directories in the current working directory. |
| `cd` | Change current working directory. |
| `mkdir` | Create new directory. |
| `rmdir` | Removes directory. |
| `touch` | Creates new file. |
| `cp` | Copy file or directory to another location. |
| `mv` | Rename or move file or directory to another location. |
| `rm` | Remove file or directory. |
| `chmod mode_parameter file_name` | Change permissions (read, write execute) of a file or directory. The `mode_parameter` is a combination of three digits, where each digit corresponds to the permission for the owner, group, and others respectively (0 - no permission, 1 - execute, 2 - write, 3 - write and execute, 4 - read, 5 - read and execute, 6 - read and write, 7 - read, write, and execute). |
| `ls -l` | Used to view the permissions of a file. |
| `chown` | Change file or directory ownership. |
| `pwd` | Print current working directory. |
| `sudo` | Run a command with superuser privileges. |
| `head` | Display first few lines of a file. |
| `tail` | Display last few lines of a file. |
| `wc` | Count the number of lines, words, and characters in a file. |
| `uname` | Print info about operating system and hardware system. |
| `grep` | Search for a pattern in a file or directory. |
| `echo` | Print a message to console. |
| `ps` | Display current running processes. |
| `less` | Display contents of a file. |
| `&&` | Command separator that allows running of multiple commands on the same line. |


## Terminologies
The following are some concepts in GitHub

| Terms | Discription |
| ----- | ----------- |
| `GitHub` | Is a collaboration platform which provides web-based graphical interface that helps manage `Git` repositories or that uses Git for versioning (creating different versions of software or code, with each representing a set of changes or updates). |
| `Git` | Is an `open-source version control system` that is used to manage and keep track of changes to `source codes`. |
| `Repository` | Is a project or storage location containing files and folders. |
| `Open-source` | Refers to a software or project for which the `source code` is designed to be publicly accessible for free, granting users the permission to use, modify, and distribute the code. |
| `Source code` | is a set of written instructions that make up a software program, written in programming language. It can be used interchangeably with `code`. |
| `Version Control System` | Also known as `revision control system` or `source control system` or `source code management system` is a software used to track and manage changes made to source codes. Examples include Git, Mercurial, and Subversion. |
| `README` | Is a file in a repository that provides info about the project. |
| `Branch` | Is a copy of a `codebase` that allows developers to work on different versions or features of that codebase. When a new branch is created, it is a clone of the original codebase (main/master). Developers can now make changes to the code on the newly created branch without affecting the original code of the main/master branch. Branches can be merged into the original branch after changes has been tested and approved.  This allows developers to work on different features or versions of the codebase simultaneously, while keeping the main branch stable and updated with approved changes. |
| `Codebase` | Is simply the collection of source code files and resources that make up a software project. |

### Curator & Contributor
* Abraham Da Costa Silvanus
* https://github.com/asdacosta

**For any questions**: asdacosta18@gmail.com
