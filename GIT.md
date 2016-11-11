##Simple Steps for adding a file from desktop to Remote Location

###Step1: 

Create a repository online in your git hub account say datasciencecoursera.

###Step2:

 After installation git hub in your desktop, u can actually go to Git bash shortcut right click on properties and assign the directory you wish to start from. (U can create a directory using mkdir command from gitbash)

###Step3: 

Now you need to create a local copy for the datasciencecoursera you have created online, u can do that by $git init, then u need to point local with remote by using $git remote add origin https://github.com/XXXX/datasciencecoursera

if u want to clone already existing u can say $ git clone /path/to/repository

Workflow of the file location will be in the following format

###Working Directory (Local) ==add==> Index (Stage) ==Commit==> HEAD

###Step4:

now create the file HelloWorld.md and place in the directory, then lets propose change in INDEX by using $ git add <filename> which gives you prompt added file.

###Step5: 

commit the changes to HEAD of local working copy with a message, this will just commit the file to Head. $ git commit -m "New file helloworld added (message)"

###Step6: 

now in order to add these changes to remote repository

###$git push origin master 
(master is the default branch when you create a repo; u can replace master with any branch ) which adds to remote server.

to update your local repo with latest commit use $ git pull.

