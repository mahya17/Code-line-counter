# Code Line Counter 📊

A Python program that counts the number of lines of code in a Python file, excluding blank lines and comments.

## About the Project

I built this project as part of **CS50's Introduction to Programming with Python** by Harvard University.

The program takes the path to a Python file as a command-line argument and counts the number of lines that contain actual code.

Blank lines and comments are not included in the final count. The program also handles invalid command-line arguments, incorrect file extensions, and files that do not exist.

## How It Works

The program expects exactly one command-line argument: the path to a Python file.

For example:

```text
python lines.py hello.py
```

If the file contains two lines of actual code along with comments and blank lines, the program returns:

```text
2
```

The program exits with an error message when:

* No command-line argument is provided
* More than one argument is provided
* The file is not a Python file
* The specified file does not exist

## What I Practiced

While working on this project, I practiced:

* Working with command-line arguments
* Using the `sys` module
* Reading files with `open()`
* Handling `FileNotFoundError`
* Checking file extensions
* Working with strings
* Detecting blank lines
* Detecting comments
* Using `sys.exit()`
* Counting lines of code

## Technologies

* Python

## What I Learned

This project helped me practice working with files and command-line arguments in Python.

I also learned how to validate user input provided through the command line and handle different error conditions using `sys.exit()`.

## Course

This project was completed as part of **CS50's Introduction to Programming with Python** by Harvard University.
