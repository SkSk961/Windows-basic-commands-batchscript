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

<img width="732" height="330" alt="image" src="https://github.com/user-attachments/assets/518e7962-4dca-450d-acf8-48484494459e" />

## COMMAND AND OUTPUT

Remove the directory "my-folder"

![Uploading Screenshot 2025-11-17 102905.png…]()



## COMMAND AND OUTPUT

<img width="291" height="51" alt="image" src="https://github.com/user-attachments/assets/b887c6ed-f93f-4cc1-b411-b37eefac7956" />

Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="417" height="56" alt="image" src="https://github.com/user-attachments/assets/eedd95af-5d87-41ee-b9d0-c34b5b1a86c8" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="395" height="60" alt="image" src="https://github.com/user-attachments/assets/6ee5e642-c6b7-473d-b86d-1acdfe00b998" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT



Remove the file hello1.txt

## COMMAND AND OUTPUT

<img width="803" height="232" alt="image" src="https://github.com/user-attachments/assets/05a728f8-4f72-44ab-a817-1f97bef9a286" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

<img width="307" height="57" alt="image" src="https://github.com/user-attachments/assets/e0c2f406-b885-48f3-97b4-7585ff6d4a44" />


List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="382" height="106" alt="image" src="https://github.com/user-attachments/assets/aa948231-a81a-4238-882e-5a088988384a" />

Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="357" height="173" alt="image" src="https://github.com/user-attachments/assets/7b0b9f48-ab32-480e-a010-b500b2475194" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT


<img width="582" height="303" alt="image" src="https://github.com/user-attachments/assets/0c779552-223e-4447-9759-04141f0ae13c" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT


<img width="497" height="310" alt="image" src="https://github.com/user-attachments/assets/afe6c036-03b6-4537-b43b-6f15fc5fdf55" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="420" height="247" alt="image" src="https://github.com/user-attachments/assets/aa6affff-5324-4fe5-9a68-b63471f83517" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="358" height="271" alt="image" src="https://github.com/user-attachments/assets/89c90de3-2556-42a5-834f-5d53f477ac0d" />


# RESULT:
The commands/batch files are executed successfully.
