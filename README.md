# WindowsFolderDeleter
A simple Power Shell script to delete default windows folders.

## Usage

### Select folders to be deleted

Open the file with Notepad++ or with an other text editor. Delete the sections from the script that correspond to the folders that you don't want to delete. 

### Run the script

Open PowerShell as an administator. Then executes:

	Set-ExecutionPolicy RemoteSigned
	& "C:\PATH\TO\SCRIPT\windowsFolderDeleter.ps1"