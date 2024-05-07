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


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
%userprofile%\Desktop\MyLab
![image](https://github.com/Nandhakumar1313/Windows-basic-commands-batchscript/assets/120230694/c206b1a2-a6cd-4a05-8be1-0e757209c1bd)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.

%userprofile%\Desktop\MyLab
![image](https://github.com/Nandhakumar1313/Windows-basic-commands-batchscript/assets/120230694/4b447d26-41f7-404f-9b36-abeade389383)
![image](https://github.com/Nandhakumar1313/Windows-basic-commands-batchscript/assets/120230694/5fdde096-136f-429f-b875-df720b5ace5f)

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
%userprofile%\Desktop\MyLab
![image](https://github.com/Nandhakumar1313/Windows-basic-commands-batchscript/assets/120230694/d7c09055-e3c0-40a6-acc8-9c7a0d074a87)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup
![image](https://github.com/Nandhakumar1313/Windows-basic-commands-batchscript/assets/120230694/7ec9d35f-de3b-471f-a9ca-6f2a6d423eb2)
![image](https://github.com/Nandhakumar1313/Windows-basic-commands-batchscript/assets/120230694/b745898c-a420-4802-8b01-515134b5f90a)


## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents
![image](https://github.com/Nandhakumar1313/Windows-basic-commands-batchscript/assets/120230694/2a79b20b-4617-4582-afe4-b7b93fb63e29)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.







@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!
## OUTPUT
![image](https://github.com/Nandhakumar1313/Windows-basic-commands-batchscript/assets/120230694/404d9504-2a72-4f94-aaed-bc617279bb62)

















# RESULT:
The commands/batch files are executed successfully.

