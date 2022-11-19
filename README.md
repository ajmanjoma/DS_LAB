# DS_LAB
Structures (also called structs) are a way to group several related variables into one place. Each variable in the structure is known as a member of the structure.


Linux C Programming
Linux is a developer’s paradise because it is an open-source operating system, freely available and offers free programming tools for all popular programming languages. In this article, we will explain you how to write, compile and run a simple C program on Ubuntu Linux. This will serve you as a foundation to move on to more complicated and useful C programs that you can write and run on Linux.

We have run the steps and commands mentioned in this article on an Ubuntu 22.04 LTS system, but it works exactly the same on other versions like Ubuntu 20.04 or on Debian 11.

To compile a simple C program, we use the Linux command-line tool, the terminal. To open the terminal, you can use the Ubuntu Dash or the key combination Ctrl+Alt+T.

Step 1: Install the build-essential packages
In order to compile and execute a C program, you need to have the essential packages installed on your system. Enter the following command as root in your Linux Terminal:

$ sudo apt-get install build-essential

Step 2: Write a simple C program

Step 3: Compile the C program with gcc Compiler
In your Terminal, enter the following command in order to make an executable version of the program you have written:

Syntax:

$ gcc [programName].c -o programName

Step 4: Run the program
The final step is to run the compiled C program. Use the following syntax to do so:

$ ./programName
