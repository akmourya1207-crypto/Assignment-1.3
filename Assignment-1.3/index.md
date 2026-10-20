Here is the complete guide and command reference to finish Assignment 1.3.

Step-by-Step Terminal Implementation
1. Open the Terminal
Windows: Open Command Prompt or PowerShell.

macOS / Linux: Open the built-in Terminal app.

2. Create the Root Folder
Run this command to create your main practice folder and immediately navigate into it:

Bash
mkdir web-development-practice
cd web-development-practice
3. Create Week Folders
Create the subfolders for your weeks using mkdir:

Mac / Linux / Windows PowerShell:

Bash
mkdir week-1 week-2 week-3
Windows Command Prompt (cmd):

DOS
mkdir week-1 week-2 week-3
4. Create an index.html File Inside Each Folder
You can quickly create empty HTML files inside each respective folder using terminal redirection:

macOS / Linux / Windows PowerShell:

Bash
touch week-1/index.html week-2/index.html week-3/index.html
Windows Command Prompt (cmd):

DOS
type nul > week-1\index.html
type nul > week-2\index.html
type nul > week-3\index.html
5. Practice Navigation, Renaming, and Deleting (Bonus Workflow Practice)
Before finishing, practice these standard commands as required by your task:

Navigate into a folder: cd week-1

Go back up to the parent folder: cd ..

Rename a folder/file (e.g., renaming week-3 to week-three):

Windows (Command Prompt): ren week-3 week-three

macOS / Linux / Windows (PowerShell): mv week-3 week-three

Delete a file/folder (if you need to clean up a mistake):

Delete a file: rm filename (Mac/Linux/PowerShell) or del filename (Windows cmd)

Delete a folder: rm -rf foldername (Mac/Linux/PowerShell) or rmdir /s foldername (Windows cmd)

6. Open the Project Folder in VS Code from the Terminal
Once you are inside your web-development-practice directory, open the entire workspace directly in VS Code by typing:

Bash
code .
Summary Record of Commands (For Your Submission)
If your assignment asks for a record of the commands you used, you can provide this exact log:

Bash
# Create and enter root directory
mkdir web-development-practice
cd web-development-practice

# Create week subfolders
mkdir week-1 week-2 week-3

# Create index.html inside each subfolder
touch week-1/index.html week-2/index.html week-3/index.html  # (Use 'type nul > ...' on Windows cmd)

# Open the project in VS Code
code .
Submission Checklist
Record of Terminal Commands: Copy and paste the block of commands shown above.

Screenshot of Final Folder Structure: Take a screenshot of your VS Code Explorer sidebar showing web-development-practice expanded to reveal week-1, week-2, and week-3 (each containing index.html).