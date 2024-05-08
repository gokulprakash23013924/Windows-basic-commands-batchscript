# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript
# Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting
@@ -24,42 +23,53 @@ Execute the necessary commands/batch file for the desired output.


# WINDOWS COMMANDS:
```
NAME:GOKUL PRAKASH M
REG.NO:212223240041
```
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.
![image](https://github.com/gokulprakash23013924/Windows-basic-commands-batchscript/assets/150231472/2a704c49-79ff-4c4e-bb68-e30b26718f9f)

![image](https://github.com/gokulprakash23013924/Windows-basic-commands-batchscript/assets/150231472/957f24d1-57f4-4633-b026-7809cb1220e8)
![image](https://github.com/gokulprakash23013924/Windows-basic-commands-batchscript/assets/150231472/b1be2797-ce38-4417-a39c-c20d2db2ee72)

## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
%userprofile%\Desktop\MyLab

![image](https://github.com/gokulprakash23013924/Windows-basic-commands-batchscript/assets/150231472/1e0b1f5c-99fb-49b4-869c-f7484331f084)

## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
![image](https://github.com/gokulprakash23013924/Windows-basic-commands-batchscript/assets/150231472/de7bfff4-d20c-4daa-960f-dc03db3bdf42)

%userprofile%\Desktop\MyLab

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
%userprofile%\Desktop\MyLab
![image](https://github.com/gokulprakash23013924/Windows-basic-commands-batchscript/assets/150231472/fa9f8d13-706c-492d-9d02-f4d99ccfb60b)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup


## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents
![image](https://github.com/gokulprakash23013924/Windows-basic-commands-batchscript/assets/150231472/9d420e3d-c8dc-4110-b3a3-591172e1a5f4)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.




@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!
## OUTPUT

![image](https://github.com/gokulprakash23013924/Windows-basic-commands-batchscript/assets/150231472/1d443d1e-d016-4cbe-83e5-949576f66808)




# RESULT:
The commands/batch files are executed successfully.

