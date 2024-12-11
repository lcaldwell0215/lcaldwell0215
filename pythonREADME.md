Write a python script that:

Has a purpose
    In the README file, explain what this script does and why it is useful
    Also, don't repeat something we've already done in class or what you did for the bash project
Takes in options and arguments
    Include a -h option to display information on how to use the script
    Handle invalid arguments with an appropriate error message
    Changes the output based on the provided args
Uses a regular expression
Reads from and/or writes to a CSV or SQL database
    (if you choose a SQL db please use sqlite so that I don't have to run a DB server)

Some ideas (feel free to come up with your own):

Email Parser and Filter
    Parse emails from a given file or directory and filter them based on specific criteria (e.g., sender, subject, date), then generate a summary or move matching emails to a new folder.
Data Cleanup Tool for CSV Files
    Clean up messy CSV data by removing duplicates, correcting formatting issues, and save a cleaned CSV
Password Manager with CSV Storage
    Allow users to add, retrieve, update, delete, and generate new passwords using a command line interface and store in a CSV
    (be aware this is terrible from a security perspective)
Todo List Manager with SQLite Database
    Allow users to add, remove, and mark tasks as completed on a todo list and store the data in an sqlite database