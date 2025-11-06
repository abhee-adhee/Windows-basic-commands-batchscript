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
<img width="475" height="60" alt="image" src="https://github.com/user-attachments/assets/ed068cee-aaca-4d40-8269-4a36b0df707d" />

## COMMAND AND OUTPUT

Remove the directory "my-folder"
<img width="681" height="452" alt="image" src="https://github.com/user-attachments/assets/a6924d41-6b8a-49a3-b9aa-6477ea2fe3d9" />

## COMMAND AND OUTPUT
<img width="611" height="119" alt="image" src="https://github.com/user-attachments/assets/c6c3b3de-d51c-4153-937c-06524b9eeb81" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="611" height="119" alt="image" src="https://github.com/user-attachments/assets/c6c3b3de-d51c-4153-937c-06524b9eeb81" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="656" height="162" alt="image" src="https://github.com/user-attachments/assets/e2490729-47cf-41b0-b3f0-1c2a43b30747" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="669" height="125" alt="image" src="https://github.com/user-attachments/assets/29ba667e-915e-464d-ad89-ca9f0e1ccaff" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="448" height="55" alt="image" src="https://github.com/user-attachments/assets/88d965b1-47c1-4231-9be9-6a1a6c15b226" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="644" height="248" alt="image" src="https://github.com/user-attachments/assets/d24f7b1d-8183-486b-bbf7-563c009e3999" />

List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="649" height="768" alt="image" src="https://github.com/user-attachments/assets/82040aed-87e4-466f-bc95-f9bc1cb90818" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="666" height="188" alt="image" src="https://github.com/user-attachments/assets/4e195afa-b7c0-4129-a82c-7a1249f4c1e7" />
## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="749" height="383" alt="image" src="https://github.com/user-attachments/assets/38a43edf-26a1-4bb0-a9c4-1f1996fdc260" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT


<img width="635" height="163" alt="image" src="https://github.com/user-attachments/assets/198c3565-972d-4689-91bc-722a80ad633e" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="435" height="190" alt="image" src="https://github.com/user-attachments/assets/63cbcfec-b839-41e1-b2aa-eabb3fb5c3cd" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="434" height="104" alt="image" src="https://github.com/user-attachments/assets/46a73b5f-647e-4e10-83c1-365004b5a8da" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="480" height="422" alt="image" src="https://github.com/user-attachments/assets/69724fa6-b162-42df-aa6d-5146ccaada26" />



# RESULT:
The commands/batch files are executed successfully.

