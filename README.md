# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"
<img width="555" height="125" alt="image" src="https://github.com/user-attachments/assets/fe9bdee8-5434-45bf-abc0-29868fae0367" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"
<img width="745" height="382" alt="image" src="https://github.com/user-attachments/assets/7aba192f-4da0-442d-b4e3-fe66344dbe6f" />


## COMMAND AND OUTPUT


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="665" height="395" alt="image" src="https://github.com/user-attachments/assets/2e7916be-ec6c-4b01-ad45-7c089677af39" />



Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="515" height="122" alt="image" src="https://github.com/user-attachments/assets/a225173c-3bd7-4399-820e-be683bcb603c" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="621" height="292" alt="image" src="https://github.com/user-attachments/assets/dd424d20-c026-462c-8b8c-c2f88e09c069" />
<img width="407" height="167" alt="image" src="https://github.com/user-attachments/assets/8adea936-fae4-499b-9fea-496bcaaaf434" />



Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="593" height="327" alt="image" src="https://github.com/user-attachments/assets/0d4c7cc7-39de-4e8c-a3cc-bc2713e695ab" />


List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="731" height="777" alt="image" src="https://github.com/user-attachments/assets/7818a554-b64a-40e7-8be9-a02076f2850b" />



Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="532" height="262" alt="image" src="https://github.com/user-attachments/assets/329098fa-05ce-4ff2-b8b3-2895850299d1" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="463" height="158" alt="image" src="https://github.com/user-attachments/assets/0124c27a-7b66-4da6-97fd-de4cc3dbf968" />




Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="661" height="305" alt="image" src="https://github.com/user-attachments/assets/0fa779cb-bb6b-4079-90c9-9e8f3b9abfae" />





Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="442" height="177" alt="image" src="https://github.com/user-attachments/assets/b0f9fba8-37f3-4d13-8bbf-430ad1285c5c" />





Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="497" height="197" alt="image" src="https://github.com/user-attachments/assets/d64f284d-39d6-4436-aab0-9f2114d5473c" />



Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="478" height="447" alt="image" src="https://github.com/user-attachments/assets/726fde39-981d-4832-9a5c-9a8e9f59e202" />




# RESULT:
The commands/batch files are executed successfully.

