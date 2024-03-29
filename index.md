![Image](cd.png)

The first screenshot is the first three examples of using the command with *no arguments*， a path to *a directory* as an argument with a path to *a file* as an argument for command *cd*. 
The working directory was /home in the first two examples and /home/lecture1 in the third example.

For the first example. the output is not an error.Running cd without arguments takes us to the home directory of the user. This is the default behavior of cd when no directory path is specified.

For the second example, By providing a directory path (Lecture1), the cd command changes the working directory to the specified directory(/home/lecture1). And the output is not an error.

For the third example, attempting to cd into a file (Hello.class) results in an error. The cd command is designed for changing directories, not files. Therefore, trying to navigate into a file will result in an error.


![Image](ls.png)

The second screenshot is the middle three examples of using the command with *no arguments*， a path to *a directory* as an argument with a path to *a file* as an argument for command *ls*. 

The working directory was /home for all three examples.

For the first example, running ls without arguments lists the contents of the current directory (Lecture one README). It provides a detailed view, showing files and directories along with their permissions and other information. So it's not an error.

For the second example, Providing a directory path (Lecture1) as an argument to ls lists the contents of Lecture1(Hello.class Hello.java messages). It's a useful way to inspect the contents of a particular folder.

For the third example, using ls with a file path (README) displays name of that specific file (README). It does not show contents, as it does with directories.


![Image](cat.png)

The third screenshot is the last three examples of using the command with *no arguments*， a path to *a directory* as an argument with a path to *a file* as an argument for command *cat*.
The working directory was /home for all three examples.

For the first example,running cat without arguments waits for user input from the keyboard. It's commonly used to concatenate and display the content of files, but without arguments, it's waiting for input.

For the second example, trying to cat a directory (Documents) results in an error. The cat command is designed for files, not directories.

For the third example, using cat with a file path (README) displays the content of that specific file in the terminal. It's a handy command for viewing the contents of files. Obviously it's not an error.
