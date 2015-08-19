# Command-Line-Notes
A place to just document useful commands and all the good stuff in the terminal I find.

## Basic Commands

| Command  | Description |
| ------------- | ------------- |
| ls | List contents (short) |
| ls -l | List contents (long) |
| ls -a | List contents w/ hidden files |
| ls -lh | Long Listing with human readable file sizes |
| ls -R | List contents recursively |
| cd | Home directory |
| cd {directory} | Change directory |
| sudo {command} | Runs command as super user |
| sudo !! | Runs sudo on previous command |
| top | Displays all active processes |
| clear | Clear screen |
| reset | Reset Screen |
| q | Quit |


## File System Management

| Command  | Description |
| ------------- | ------------- |
| pwd | List current working directory |
| touch {file} | Create file |
| cat {file} | Concatenate file and display on command line |
| rm {file} | Remove file (permanent) |
| rm -rf {directory} | Delete folder and its contents (Recursively force remove) |
| mv {file} {newFile} | Move/Rename file |
| cp {file} {newFile} | Copy to file |
| touch {file} {directory} | Copy to folder |
| mkdir {directory} | Create directory |
| rmdir {directory} | Delete Directory |


## Pipe
| Command  | Description |
| ------------- | ------------- |
| {command} \| {command} | Push output of command 1 into command 2 |
| {command} > {file} | Push output to a file (overwrite) |
| {command} >> {file} | Push output to a file (append) |

// TODO: Add flag descriptions

## History
| Command  | Description |
| ------------- | ------------- |
| history n | Display previous commands inputed (limit to n) |
| ctrl + r | Search through command history |
| !!  | Execute previous command |


## Help and Documentation
| Command  | Description |
| ------------- | ------------- |
| {command} --help | Display help |
| man {command} | Display command's documentation |
| whatis {command} | Display one line description |
