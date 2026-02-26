## Basic System Info
- set: displays all current environment variables, in THM room it was used to display the path
- ver: displays the OS version
- systeminfo: displays various info about the system
- command_name | more: allows you to view long blocks of text in pages
- help: provides info about a specific command
- cls: clears command prompt screen
- command_name /?: pulls up help page on that command

## Network Troubleshooting
- ipconfig: to check network info
- ipconfig /all: for more info about your network configuration
- ping target_name: test connectivity between two devices
- tracert: traces the network route traversed to reach the target and it returns # of routers traversed
- nslookup: looks up host or domain and returns its ip address
- netstat: displays current network connections and listening ports

## File and Disk Management
- cd: displays current directory
- cd target_directory: change to another directory
- cd ..: goes up one level
- dir: views child directories (dir /a to view hidden files)
- tree: visually represent the child directories and subdirectories
- mkdir directory_name: makes a directory
- rmdir directory_name: removes a directory

## Working with Files
- type file_name: Displays the contents of a text file.
- more file_name: Shows a file's content one page at a time.
- copy file_name: Copies a file to a new location.
- move file_name]: Moves a file to a new location.
- del file_name or erase file_name: Deletes a file.
- We can use the wildcard character * to refer to multiple files. For example, copy *.md will copy all files with the extension md

## Task and process management
- tasklist: lists running processes
- tasklist /FI "imagename eq process_name": Filters the tasklist for a specific process (e.g., notepad.exe)
- taskkill /PID pid_#: Terminates a process by its process ID (PID)
