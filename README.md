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

## Shortcuts

| Command  | Description |
| ------------- | ------------- |
| Tab | Autocomplete |
| Ctrl + C | Kill process |
| Ctrl + D | Exit shell |
| Ctrl + L | Clear Screen |
| Ctrl + Z | Puts whatever you are running into a suspended background process. fg restores it. |
| Ctrl + A | Go to beginning of current line |
| Ctrl + E | Go to end of current line |
| Ctrl + U | Clears line before cursor position |
| Ctrl + K | Clears line after cursor position |
| Ctrl + W | Deletes word before cursor |


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
| grep {pattern} {file} | Searches file(s) for specific pattern |
| mkdir {directory} | Create directory |
| rmdir {directory} | Delete Directory |


## Pipe
Piping is essentially chaining the outputs of a command into the input of the following command.

| Command  | Description |
| ------------- | ------------- |
| {command} \| {command} | Push output of command 1 into command 2 |
| {command} > {file} | Push output to a file (overwrite) |
| {command} >> {file} | Push output to a file (append) |

**Example:** Grab all instances of foo from command line history - 
``` history | grep foo | less ```


## Flags
Flags are command line parameters appended to a command to specify certain settings, multiple flags can be used in combination. **Note -** The following examples will be based on the command ```ls```.  Flags will vary depending on the command they are affiliated with. The following examples are just "common" flags that you may or may not see in other commands.

| Command  | Description |
| ------------- | ------------- |
| -a | All (including files starting with .) |
| -A | Almost all (not including files starting with .) |
| -d | List directory entries instead of contents |
| -f | Do not sort |
| -h | Human readable |
| -I {Pattern} | Do not show entries with {Pattern} |
| -r | Reverse order |
| -R | Recursive |
| -s | Print size |
| -S | Sort by size |

**Example:** Grab all files at a specific location with a specific pattern - 
``` grep -l -f /src/bin/foo bar ```


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


TODO: BG/FG, heredocs, CURL/netcat/wget/telnet
