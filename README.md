# bash
**Bash** is a scripting language that is used in the **command line**. Bash was around long before the coveted mouse that we are used to today. Consider Bash a personal assistant that can perform many functions in one command center. Bash scripting is used in Cloud9 for various reasons:
- Run a specific file
- Run a server
- Open a specific file
- Download a gem, framework, or language
- Update a gem, framework, or language 
- Navigate the file structure

Bash script commands can also perform a number of smaller tasks:
- Tell you the date and time {`date` + `enter`)
- Display a calendar for the current month (`cal` + `enter`)
- Display a calendar for a specific year (`cal 2016` + `enter`)
- Display a message on the screen (`echo your_message` + `enter`)

# the_Terminal
The **Terminal** is the command center for Bash scripts. The Terminal accepts commands that allow text-based access to your coding environment and ecosystem. This includes your file structure, any installed frameworks, and any programming languages being used (no mouse needed). 
- This is in contrast to the GUI (graphical user interface), which is what we are all used to seeing when we open our computers (desktop, folders, mouse, dropdown menus, etc.). The Terminal provides a command line interface that allows you to input a number of commands to operate your machine.  

The Cloud9 Terminal is positioned at the bottom of your window with an open tab containing the word `bash` (makes sense now, right?). Your terminal includes:
- Your username
- Your working file directory
- A dollar symbol `$`
  - This symbol is used to separate typed commands from your username and working directory  
 
![1](http://i.imgur.com/hGcgtLy.png)

###### Note: Each Terminal open is referred to as a **shell**. You can open a new shell by clicking the `+` button near the current open tab and selecting `New Terminal`.   


# bash_commands
To run a Bash script command, enter the command into the Terminal shell and press `enter`. Below is a list of useful Bash scripting commands to run in your Terminal shell:  

| Action                                                                  | Keybinding              |
|-------------------------------------------------------------------------|-------------------------| 
| Clear Shell Screen                                                      | clear                   |
| Change directory to root directory                                      | cd                      |
| Change directory to current directory                                   | cd .                    |
| Change directory to go back one directory in the file tree              | cd ..                   |
| Change directory to go back two directories in the file tree            | cd ../..                |
| Change to a specified directory inside the current working directory    | cd directory_name       |
| Make a new directory within the current working directory               | mkdir directory_name    |
| Create a new file within the current working directory                  | touch file_name         |
| Remove a directory                                                      | rm -rf directory_name   |
| Remove a file                                                           | rm file_name            |
| Run a Ruby file                                                         | ruby file_name.rb       |

These commands will become second nature to you as you progress with your programming and I bet you will become more efficient navigating a command line than using a mouse!

##### Now start scripting! Don't be bashful... 
![2](http://i.imgur.com/iM4CI8m.gif)

---  
[Course home](https://github.com/Coderdotnew/intro_web_apps_001) 
