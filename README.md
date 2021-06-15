# Linux Commands
- `mkdir name_of_directory`: Create a directory
- `cd name_of_directory`: Change directory
- `cd` OR `cd ..`: Come out of directory
- `uname -a`: Shows who you are using the machine as
- `pwd`: Shows where you are
- `touch name_of_file`: Creates a file
- `nano name_of_file`: Creates a file and goes inside the file to edit
  - `CTRL+X`: Leave nano
- `ls`: List all
  - `ls -a`: List all, including hiddden 
- `rm -rf name_of_file`: Delete file
- `rm -rd name_of_directory`: Delete directory
- `ps`: Process Status, see what you are running
  - `-a`: Shows information on all users
  - `-x`: Shows information about processes without terminals
  - `-u`: Shows additional information
  - `-e`: Displays extended information

## Stopping Processes
- If the process is running in the foreground, simply send `CTRL + C`, which will exit the command.
- If the process you wish to stop is in the background:
  - Find the job ID using the `ps` command
  - `kill job_ID`: Will kill the process

## Changing permissions
- `chmod -flag file_name`: Will change the permission of the file depending on the flag you assign.
- Before the chosen flag, add a `-` to remove this permission or `+` to add this permisison.
- Flags:
  - `r`: Read
  - `w`: Write
  - `x`: Execute



- To check hidden files and directories:
- How to do process management:
- See what's currently running on your system:
- Killing a process/crashed process:
- Check any processes running in foreground and background jobs:
- Stop/Kill any process running in foreground and background jobs:
- How to change permissions:
- How to change permissions for files/dir
- What does 777,4000,600,r,w,x,
- How to use head, tail, sort, nl (number line), wc (word count)
- What is pipping and redirection
- What is STDIN standard input and output
