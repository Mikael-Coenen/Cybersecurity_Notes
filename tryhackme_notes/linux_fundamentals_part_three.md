### Terminal text editors
- Nano: To create a file with nano do this command: nano filename
- VIM: a more advanced editor that allows you to create your own keyboard shortcuts, etc

## wget command
- Allows us to download files from the web via HTTP
- We just need to provide the address of the resource we want to download
- Ex: wget https://assets.tryhackme.com/additional/linux-fundamentals/part3/myfile.txt

## SCP
- Secure copy
- Allows you to transfer files between two computers using the SSH protocol to provide both authentication and encryption

## Web server
- Ubuntu machines come pre-equipped with Python3
- Python has a module called HTTPServer which allows you to quickly set up a HTTP web server

## Processes
- Processes are the programs running on your machine
- Each process has an ID called PID which increments in the order the process starts
- ps: command that provides a list of running processes
- ps aux: command that tells you processes run by other users and that dont run from a session
- top: command that gives you real time stats about the processes running on your system instead of a one-time view
- kill: using the kill command then the associated PID you can terminate a process
- When a system boots systemd is one of the first processes that are started
- Processes can run in two states: in the background and foreground
