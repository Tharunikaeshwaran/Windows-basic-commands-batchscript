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

## COMMAND AND OUTPUT
<img width="1092" height="68" alt="image" src="https://github.com/user-attachments/assets/762cc129-cf13-444a-af95-42b731524d40" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT

<img width="1081" height="102" alt="image" src="https://github.com/user-attachments/assets/7dd2cced-2dd2-44f4-9b24-5cd9da5e3932" />

Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="1015" height="767" alt="image" src="https://github.com/user-attachments/assets/fa2a7bde-ee3f-4c43-929b-3114ffa563d4" />

Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="1337" height="250" alt="image" src="https://github.com/user-attachments/assets/67c6df39-9d55-4040-8443-d68ea4732fa0" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="1243" height="230" alt="image" src="https://github.com/user-attachments/assets/c638db5f-4163-4362-8f07-1264a0feee1e" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="888" height="90" alt="image" src="https://github.com/user-attachments/assets/8eebf33a-d337-4f70-b71f-89b71fcb6a9c" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="518" height="757" alt="image" src="https://github.com/user-attachments/assets/997f8408-3cf0-473a-bcf0-b0a7f6df9d17" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="557" height="198" alt="image" src="https://github.com/user-attachments/assets/11841fa2-92a8-40e1-9e6e-3fbe12f336b8" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="622" height="132" alt="image" src="https://github.com/user-attachments/assets/2544ea03-1d33-499c-b402-98366e83b34d" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT


<img width="777" height="302" alt="image" src="https://github.com/user-attachments/assets/2d18c5b5-ad1f-42bf-a30c-098af0e3ba54" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="541" height="267" alt="image" src="https://github.com/user-attachments/assets/695f9f63-2eb8-4939-99f9-97b0f999c50f" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="750" height="262" alt="image" src="https://github.com/user-attachments/assets/0e49517c-e681-4536-b9f4-aee9656607f4" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="378" height="535" alt="image" src="https://github.com/user-attachments/assets/fca2f532-b576-4ac6-8679-96370a80c226" />




# RESULT:
The commands/batch files are executed successfully.

