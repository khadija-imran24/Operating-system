# Khadija Imran                                          2022-CS-171

# Operating System Lab 3

## Task1

1. **Create a file named “19f-XXXX.txt”. File must contain at least 10 lines.** 
2.  **Create another file named “your name.txt”. File must contain at least 10 lines.**

![2](2022-CS-171_OS_SE_Lab3\imgs\2.png)

![3](2022-CS-171_OS_SE_Lab3\imgs\3.png)

![1](2022-CS-171_OS_SE_Lab3\imgs\1.png)

3. **Merge the data of both files.** 
4. **Redirect the output to a new file.** 

![4](2022-CS-171_OS_SE_Lab3\imgs\4.png)

![5](2022-CS-171_OS_SE_Lab3\imgs\5.png)

5. **Display the first two lines of first file.**

6. **Display the last two lines of second file.**

   ![6](2022-CS-171_OS_SE_Lab3\imgs\6.png)

7. **Finds the string (your roll#) from the first file.** 

8. **Grant the execute permission of the second file to the group.** 

   ![7](2022-CS-171_OS_SE_Lab3\imgs\7.png)

   ![8](C:\Users\khadija imran\Downloads\OSLab-main\OSLab-main\2022-CS-171_OS_SE_Lab3\imgs\8.png)

**9. Remove the write permission for the owner**

![9](2022-CS-171_OS_SE_Lab3\imgs\9.png)

**10.Now Mr. Tom suddenly lost the track of his current location. Help him find his location.** 

**11.He wants the list of all files present on Desktop directory.** 

**12.Now he wanted to create a folder of his personal files and pictures named as your roll#.** 

**13.Display the current time.**

 **14.He is done with the task and he is happy with your work. He want to display a thankyou message.**

![10](2022-CS-171_OS_SE_Lab3\imgs\10.png)

## Task2:

1. **Create a file named “19f-XXXX_OS-lab_rules.txt” using linux commands. The file must contain all lab rules covered in first lab.** 

   ![11](2022-CS-171_OS_SE_Lab3\imgs\11.png)

2. **You want to set the rights of created file to this (- rwx r-x r--). For these rights, you are required to convert the given rights in numeric format using binary number system procedure covered in lecture. Show complete working.** 

   Firstly , the number for read permission is 4, for write is 2 and for execute is 1.

   Now for this (- rwx r-x r--). we need 4+2+1 which is for owner, 4+0+1 which is for group and 4 which is for others . It means user can read write and execute the file ,group can read and execute file and other can read only the file. so in command we need to write 751 like

   ​                                        *sudo chmod 754 file_name*

3.  **Now use the derived number to change the permission of a file using chmod command.**  

   ![12](2022-CS-171_OS_SE_Lab3\imgs\12.png)

4. **Append the output of ls command to created file**

![13](2022-CS-171_OS_SE_Lab3\imgs\13.png)
