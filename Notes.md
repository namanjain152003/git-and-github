Git is a free and open-source distributed version control system used to track changes in source code during software development. It's a powerful tool that allows developers to collaborate on projects, manage different versions of their work, and easily revert to previous states if needed.

working directory ---> staging area ---> git repository.



To initialize git we simply write "git init".

the command, "git add". is used to add the changes in the staging area

git status is used to check the current status of the file

So the command is git commit -m " " is used to commit and add commit message .

by git log command is used to check the log of the commits.

git add .  can be used to add all files together in one go 
dot (.) to specify everything inside this current directory.

git diff <file name> is used to see the differnce between the staging area and the working area.

git diff --cached <file name> is used to see the staged changes.

git checkout<file name> will rollback to the last commited version of that file..