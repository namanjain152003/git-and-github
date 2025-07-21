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

git remote add orgin <github url> is used in terminal to add our repository in which our data should be saved.

git push -u origin main is used to push all the commits on our github repo..

git rm --cached -r .   is used to remove the folders from the staging area

.gitignore is used to avoid the files and folder that are added in this so that they cant be added in the repo like apikey , passwords etc

git clone <url> is used to clone others repository in our own local system...

branching means making another branch from the main branch so that it can another code which is not in main branch but can be added later..

git branch command give the available branches 
git branch <branch name > is used to make new branch
git checkout <branch name> is used to shift to that branch 

merging is used when we what to do something extra but aside than the main branch of code and that other branch code is worked well then we merge it with the main branch

fork in github is used to copy the github repo in our account and can make changes in them

by make a pull request we can request the author to add the changes in their orginal code as well this is how open source contribution works



