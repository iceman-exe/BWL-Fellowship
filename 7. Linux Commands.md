Linux commands:

Linux commands are case sensitive and can take arguments and flags, when required. Arguments are simply passed as paths and filenames and flags are preceded by a – or --. All commands can take multiple flags and most can take multiple arguments.

    • info: Displays information about other commands. Displays a list of all commands with short descriptions if no argument is passed. If another command is passed as an argument, it displays detailed information about that command and its usage.
    • man: Displays a manual page for the command passed as argument.
    • --help: A help flag built into the bash shell. Provides a very brief summary of the commands functions and the purpose of some of its flags.
    • clear: Clears the terminal screen.
    • pwd: Print working directory. Prints the current directory being navigated.
    • ls: Lists files and directories. Without an argument, it displays the contents of the current directory but it can also take an argument path to another directory to list its contents. It can take various flags:
            ▪ -l for detailed list, 
            ▪ -a to show hidden files, 
            ▪ -t to sort by time, 
            ▪ -h to show file and directory sizes in human readable format, 
            ▪ -R to list files and directories recursively, 
            ▪ -r to reverse sort the list.

    • cd: Change directory. Can navigate to anywhere in the system using arguments.
            ▪ .. to go back one directory, 
            ▪ no arguments or ~ to return to the home directory, 
            ▪ a specific path/ directory name to go to that directory,
            ▪ / to go to the root dir

    • mkdir: Make a new directory. Takes the name of the directory to be created as first argument and location of creation as second argument. Passing multiple arguments creates multiple directories at the location specified by the last argument. 
            ▪ -p for parent directory in order to make a directory tree with just one argument.

    • touch: Create a blank new file. The argument should be the name of new file. Multiple arguments can be passed to create multiple files.
    • cat: Can be used to read files or place content in to files. The argument is the name of the file to be read
            ▪ Multiple arguments can be used to concatenate contents of multiple files and read them all at once,
            ▪ > [filename] to output to filename

    • rmdir: Remove an empty directory. Pass the name of the directory to be deleted as the argument. Can only be used to delete empty directories.
            ▪ -p to delete entire directory tree

    • rm: Remove directories and files. Can also be used to delete files of certain types using the wildcard operator and entire directories along with their contents.
            ▪ -r for recursive,
            ▪ -f for force, 
            ▪ -v for verbose mode, 
            ▪ *(wildcard) to del everything in a directory

    • cp: Copy files and directories from one location to another. First argument is the file to be copied including its path, and the second argument specifies where to copy the file to. Multiple arguments can be passed to copy multiple files to single location.
            ▪ -v for verbose mode,
            ▪ -r to copy recursively, 
            ▪ * to copy everything in a directory,
            ▪ . as the last argument to copy to the current directory,
            ▪ [a]* to copy all files that start with a, 
            ▪ *.log to copy all files of type .log,

    • mv: Move file(s) from one location to another.  First argument should be the file to move and the last argument should specify the location to move to. This command can also be used to rename files and folders by not specifying a path in the arguments.
            ▪ -v for verbose mode,
            ▪ * wildcard can also be used to move all files of certain type or with certain name or all files in a directory,
            ▪ mv doesn’t need -r, it always moves files recursively by default

    • ln: To make a link to file. A soft link is a short cut to the original file, while a hard link creates a mirror file. A soft link breaks if any changes occur to the original file whereas a hard link works even after changes to original files name.
            ▪ -s to make a soft link, 
            ▪ default is hard link, 

    • less: Read files from top to bottom. The argument should be the name of the file to be read.
    • more: Read files from top to bottom. This command only scrolls down, not up.
    • date: Displays the current system date and time.
    • id: Returns the current users gid, uid and groups.
    • whoami: Returns the current user.
    • who: Which users are logged in and how they are logged in(tty, ssh etc)
            ▪ -a to display all users

    • w: Returns all logged in users and interfaces they are logged in through.
    • history: View the command history.
    • logout: Log out the currently logged in user.
    • exit: Exit the current terminal session.
    • shutdown: Shutdown the system.
            ▪ -r to reboot, 
            ▪ argument now or 0 to shutdown immediately

    • reboot: Reboot the system.
    • init: Shutdown(init 0) or restart(init 6) the system.


Visit this page for more information about the difference between info, man and help(https://unix.stackexchange.com/questions/19451/difference-between-help-info-and-man-command)
