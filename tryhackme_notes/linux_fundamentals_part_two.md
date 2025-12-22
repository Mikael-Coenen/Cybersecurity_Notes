- SSH: allows you to remotely execute commands on another device, data is encrypted when sent over a network
- To use SSH you need the IP address of the remote machine, and credentials to login that machine
- To construct a command to log in to the remote machine using SSH: the command to do so is ssh and then the username of the account, @ the IP address of the machine.

- Flags and switches can extend the behavior of commands, adding these keywords to commands allows us to do more
- For example, ls lists all visible files, but ls -a lists all files, including the hidden ones
- Doing --help will show all the options a command accepts
- Man page is the manual page and gives documentation on Linux commands by doing ex: man ls

New commands learned:
- touch: create file
- mkdir: make a folder
- cp: copy a file or folder
- mv: move a file or folder (can use to just rename files)
- rm: remove a file or folder (need to use -R switch for folders)
- file: determine the type of a file

- In Linux, permissions are highly granular, allowing a specific user to own a file while a designated group of different users can have separate permissions
- You can switch between users with the command: su
- The -l switch for the su command starts a login shell for the target user

Common directories:
- /etc: stores system files that are used by your OS system
- /var: stores data that is frequently accessed or written by applications running on the system
- /root: home directory for the root user
- /tmp: stores data that only needs to be accessed once or twice, gets deleted when computer gets restarted
