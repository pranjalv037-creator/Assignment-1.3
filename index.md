Assignment 1.3 — Terminal & Developer Workflow


Aim


To create a project folder structure using terminal commands and practise basic file and folder operations.
1. Creating the Project Folder
First, open the terminal and type the following command:
mkdir web-development-practice

This command creates a folder named web-development-practice.


2. Creating Week Folders
Enter the project folder:
cd web-development-practice

Create three folders inside it:
mkdir week-1 week-2 week-3

3. Creating index.html Files
Create an index.html file inside each week folder:
touch week-1/index.html
touch week-2/index.html
touch week-3/index.html

These commands create an HTML file in each folder.
4. Navigating Between Folders
To enter the first folder:
cd week-1

To return to the parent folder:
cd ..

To enter the second folder:
cd week-2

To return to the parent folder again:
cd ..

5. Renaming and Deleting Folders
To rename a folder from week-3 to week-3-renamed:
mv week-3 week-3-renamed

To rename it back to its original name:
mv week-3-renamed week-3

To create and delete a temporary empty folder:
mkdir temp-practice
rmdir temp-practice

The mkdir command creates a folder, while rmdir removes an empty folder.
6. Opening the Project in VS Code
To open the project folder in Visual Studio Code, type:
code .

This command opens the current project folder in VS Code. The VS Code command-line tool must be installed and available in PATH.
7. Final Folder Structure
web-development-practice/
├── week-1/
│   └── index.html
├── week-2/
│   └── index.html
└── week-3/
    └── index.html