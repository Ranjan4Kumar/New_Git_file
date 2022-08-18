# New_Git_file

# Screenshot
![GitBasiccommands](https://user-images.githubusercontent.com/106957343/185361665-dccff2e6-dbcb-43db-9934-04091d1e6a6a.png)

This file is only for practice purpose not for doccumentation purpose.
Git command to clone repo from remote:

git clone <github url>
  
Git command to check log:
git log
Git command for branches:
git branch - check current branch
git branch <new branch name> - create new branch
git checkout <branch name> - move to another/new branch
git checkout -b < new branch name> - create a new branch and move to it
Git command to update local with remote
git pull
git pull <branch name>
git fetch
Git commands to push to remote repo
git add .
git status
git commit -m "<message you want to log>"
git push origin <branch name>
Git commands to set email and name:
git config --global user.name <username>
git config --global user.email <email>
Git command to set remote:
git remote add <github url> (edited) 
:white_check_mark:
13

New



 #Windows
  
  
Hi team, with the new Windows 11 update, some PCs might not allow you to run django commands or activate environment.
Kindly follow the steps below to fix the issue:
Create a new Directory.
python3 -m venv env
  
Open another PowerShell with runAsAdministrator.
  
run the command: set-ExecutionPolicy unrestricted  Please Note: Student has to type the command, you will not have access to type.
 Close the admin Powershell
  
Activate environment using: ./env/Scripts/activate
  
Install Django: pip3 install django
  
Start Django project: python3 -m django startproject <project-name>
Continue with the Video
  
Please Instruct the student to:
Run windows powershell or VSCode. Not command promt as it will not allow to run unix commands
  
Activate environment everytime he/she runs the project: ./env/Scripts/activate
  
To deactivate: deactivate
CC: 
@Rajeswari
:white_check_mark:
5

