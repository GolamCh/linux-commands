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
- `head file_name`: Shows the first 10 lines of the file
  - The value of the number of lines shown can be changed as follows: `head -{number of lines} file_name`
- `tail file_name`: Shows the last 10 lines of the file
  - The value of the number of lines shown can be changed as follows: `head -{number of lines} file_name`
- `nl file_name`: Gives the number of lines in the file
- `wc file_name`: Gives the number of words in the file

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
- Other Flags:
  - These flags will not require a `+` or `-`
  - `777`: Everybody can do everything to this file
  - `400`: Protects against accidental overwriting
  - `600`: A private file, only changeable by the user who enetred the command
- `chmod` can be applied to either files or directories.

## Piping & Redirection







- What is STDIN standard input and output
