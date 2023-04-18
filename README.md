# File Organizer
This Python code is designed to organize files in a specified directory into subdirectories based on their file extensions.

## Getting Started
To use this script, you need to specify the path to the directory containing the files you want to organize. The variable path is defined at the beginning of the code and should be set to the directory path.

The code also defines a list of folder names folder_names where the organized files will be stored based on their extensions.

## Organizing Files
The code checks each file in the directory to see if it has an extension that matches one of the extensions in the folder_names list. If a match is found and the folder for that extension does not already exist, the script creates a new folder with the corresponding name.

Once the folders are created, the script then moves the files to their corresponding folders based on their extensions.

## Running the Script
Simply run the script in your preferred Python environment. Once the script completes, you will see the message "All done!" in the console.

Note: the code uses the shutil and os modules, which must be imported before running the code.
