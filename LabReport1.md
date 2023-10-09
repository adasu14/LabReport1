# Lab Report 1

In this blog post, we'll explore three fundamental filesystem commands: cd, ls, and cat. These commands are essential for navigating, listing files, and viewing content within directories in a Unix-based system. We'll demonstrate different ways of using these commands, showcasing their versatility and practicality.

# cd
The cd command, short for "change directory," allows us to change our current working directory.

__Using cd with no arguments__

![Alt text](image.png)

Working directory: The home directory
<br>
Output Explanation: Using 'cd' without arguments takes us to the user's home directory
<br>
Error Indication: No Error
<br>
<br>

__Using cd with a path to a directory as an argument__

![Alt text](image-1.png)

Working Directory: The home directory
<br>
Output Explanation: The cd command with a directory path to 'lecture1' as an argument changes the working directory to 'lecture1'.
<br>
Error Indication: No error.


__Using cd with a path to a file as an argument__

![Alt text](image-2.png)

Working directory: The current working directory before executing the command
<br>
Output Explanation: Using cd with a file path as an argument results in an error because cd can only change to directories, not files.
<br>
Error Indication: Error: Not a directory.



# ls
The ls command, which stands for "list," is used to list files and directories in a directory.

__Using ls with no arguments__

![Alt text](image-3.png)

Working Directory: The home directory.
<br>
Output Explanation: Running ls without arguments lists the files and directories in the current directory. The only directory in 'home' is 'lecture1' so this is listed. Any files in 'home' are in 'lecture1' so are not displayed.
<br>
Error Indication: No error.

__Using ls with a path to a directory as an argument__

![Alt text](image-4.png)

Working Directory: The home directory.
<br>
Output Explanation: The ls command with a directory path of 'lecture1' lists the files and directories in 'lecture1'.
<br>
Error Indication: No error.

__Using ls with a path to a file as an argument__

![Alt text](image-5.png)

Working Directory: The current working directory before executing the command.
<br>
Output Explanation: Using ls with a file path as an argument lists the specified file, but it's generally used for directories.
<br>
Error Indication: No error.

# cat
The cat command is used to display the contents of a file.

__Using cat with no arguments__

![Alt text](image-6.png)

Working Directory: The home directory.
<br>
Output Explanation: Running cat without arguments results in an error because it expects a file to display.
<br>
Error Indication: Error: No such file or directory.

__Using cat with a path to a directory as an argument__

![Alt text](image-7.png)

Working Directory: The home directory.
<br>
Output Explanation: The cat command with a directory path as an argument results in an error because it expects a file, not a directory.
<br>
Error Indication: Error: Is a directory.

__Using cat with a path to a file as an argument__

![Alt text](image-8.png)

Working Directory: The current working directory before executing the command.
<br>
Output Explanation: The cat command with a file path as an argument displays the contents of the specified file.
<br>
Error Indication: No error.