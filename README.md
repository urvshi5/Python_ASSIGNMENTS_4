# Files, Exceptions, and Errors in Python Task
This project contains Python code demonstrating fundamental file handling operations. The project is divided into two main tasks: one focusing on reading and analyzing an existing file, and the other on writing new data to a file.
## Table of Contents 
1.  Task 1: Reading and Analyzing a File
2. Task 2: Writing and Appending to a File

## Task 1: Reading and Analyzing a File
**Filename:** `file_reader.ipynb`

### Functionality
This script is designed to open and process an existing text file named sample.txt. It reads the file's content, counts the total number of lines and words, and prints a summary. The program is built to be robust and provides a clear error message if the input file cannot be found.
### Key Features

- **File Reading**: Utilizes the modern with open(...) syntax, which guarantees that the file is properly closed after use.
- **Text Analysis**: Reads the file line by line to perform calculations, making it memory-efficient.
- **Line & Word Counting**: It programmatically counts lines by iterating through the file and counts words by splitting each line into a list of strings.
- **Robust Error Handling**: A try-except block specifically catches FileNotFoundError to prevent the program from crashing and to provide a user-friendly error message.

## Task 2: Writing and Appending to a File
**Filename:** `file_writer.ipynb`
### Functionality
This script demonstrates how to create and write data to a text file named output.txt. It prompts the user for input, writes that input to the file (overwriting any previous content), and then appends a second, predefined line to the end of the file before displaying the final result.
### Key Features
- **User Interaction**: Takes user input directly from the console using the input() function.
- **Write Mode ('w')**: Opens the file in write mode to create the file and write the initial content. This mode will erase the file if it already exists.
- **Append Mode ('a')**: Re-opens the file in append mode to add new data to the end of the file without deleting the original content.
- **File Creation**: Automatically creates output.txt if it does not already exist in the directory.
