# EX 08 - WINDOWS BASIC COMMANDS BATCHSCRIPT
## Developed by : AKASH G
## Register No. : 212224100004
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
## A. Create a directory named 'my_folder'
## COMMAND AND OUTPUT

```
mkdir my_folder
```

<img width="460" height="76" alt="image" src="https://github.com/user-attachments/assets/eba88d52-2494-4bc4-bd0f-7ea98b33f284" />

## B. Remove the directory "my-folder"
## COMMAND AND OUTPUT
```
rmdir my_folder
```
<img width="433" height="73" alt="image" src="https://github.com/user-attachments/assets/0c85155c-c08e-4c83-a6e6-7d86c40447c2" />

## C. Create the file Rose.txt
## COMMAND AND OUTPUT
```
COPY CON Rose.txt
A clock in a office can never get stolen
Too many employees watch it all the time
^Z

dir Rose.txt
```
<img width="795" height="359" alt="image" src="https://github.com/user-attachments/assets/fc94459f-fc2c-4658-99d6-1e9429b913f1" />

## D. Create the file hello.txt using echo and redirection
## COMMAND AND OUTPUT
```
echo “hello world” > hello.txt
type hello.txt
```
<img width="605" height="101" alt="image" src="https://github.com/user-attachments/assets/ab12898a-42c5-4fab-827c-0f52d8cf2c94" />

## E. Copy the file hello.txt into the file hello1.txt
## COMMAND AND OUTPUT

```
copy hello.txt hello1.txt
```

<img width="558" height="114" alt="image" src="https://github.com/user-attachments/assets/15b9205e-2ad8-46f3-b9fe-0b64dce3e7f9" />

## F. Remove the file hello1.txt
## COMMAND AND OUTPUT
```
del hello1.txt
```
<img width="585" height="95" alt="image" src="https://github.com/user-attachments/assets/f899c8d4-82f1-40da-8701-728dcbc1de2d" />

## G. List out the file hello1.txt in the current directory
## COMMAND AND OUTPUT
```
dir hello1.txt
```
<img width="590" height="173" alt="image" src="https://github.com/user-attachments/assets/db3b134b-6b98-4f72-ac45-84e687e551f3" />

## H. List out all the associated file extensions 
## COMMAND AND OUTPUT
```
assoc | more
```
<img width="754" height="809" alt="image" src="https://github.com/user-attachments/assets/2e98aa65-d20d-4808-aad1-760156c88ea7" />
<img width="573" height="320" alt="image" src="https://github.com/user-attachments/assets/eb4cfd2b-cb5a-40f6-9e8c-e048d38726da" />

## I. Compare the file 'hello.txt' and 'rose.txt'
## COMMAND AND OUTPUT
```
fc hello.txt Rose.txt
```
<img width="517" height="263" alt="image" src="https://github.com/user-attachments/assets/83fc322b-6c58-43b9-b060-5129ff6ddcd9" />

## Exercise 2: Advanced Batch Scripting
## A. Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".
## OUTPUT : 



## B. Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
```
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number. 
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.
```
## OUTPUT : 

## C. Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.
## OUTPUT :


## D. Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.
```
Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):
```
## OUTPUT :


## E. Write a batch script that displays a simple menu with three options:
```
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.
```

## OUTPUT :



# RESULT:
The commands/batch files are executed successfully.

