# lab-bash
lab-bash
Introduction
In this lab we are going to practice with bash, a shell and command-line language!

Setup
Fork the repo in your git hub account and then clone the folder "lab-bash" to your machine and navigate to it folder.

Check the contents of the folder using the "ls" command

$ ls
and you should see the following:

exercises  inputs  lorem  lorem-copy  modules  outputs  README.md
Stay in the same directory/folder and complete the following exercises.
Exercises
Using the echo command print in console "Hello World". Here is some info about echo command [https://discuss.codecademy.com/t/what-are-practical-uses-of-the-echo-command/394788]
Create a new directory called new_dir.
Delete/Remove the directory new_dir.
Copy the file sed.txt from the lorem folder and paste it to the folder lorem-copy folder.
Copy the other two files from the lorem folder to lorem-copy folder in just one line using semicolon ;.
Show the sed.txt file content from the lorem folder.
Show the at.txt file and lorem.txt file contents from lorem folder.
Print the first 3 rows in sed.txt file from lorem-copy folder.
Print the last 3 rows in sed.txt file from lorem-copy folder.
Add Homo homini lupus. at the end of sed.txt file in the lorem-copy folder.
Print the last 3 rows in sed.txt file from lorem-copy folder. You should see Homo homini lupus..
sed command is used to replace the text in a file. Use the sed command to replace all occurances of et with ET in the file at.txt file present in the folder lorem. You can use the following link to refer to sed commands [https://www.linode.com/docs/guides/manipulate-text-from-the-command-line-with-sed/] Check the contents of the sed.txt file using cat command.
Find who is the system user.
Find the current path of the directory you are in.
List all files with the extension .txt in lorem folder.
Count the rows in sed.txt file from lorem folder. Look concatenate cat and wc with the pipe |.
Count the files which start with lorem in all directories.
Bonus
Store your name in a variable with read command.
Print that variable.
Create a new directory named with variable name.
Remove that directory.
