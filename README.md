# Intro

Command to commit from git to remote repo

Get into to the directory you wanted to uploaded

Type in the following command

## Upload tO REPO

	git init

To add all the files in the directory

	git add .

To comment the commit you make

	git commit -m "Intial commit"

Adding the remote repository

	git remote add origin https://github.com/sangethmathewjohn/Test.git

To push the commit
	
	git push origin master


## Getting INFO

TO get info about commits made, time, user etc..

	git log

To get about each commit by commit id [Hexa decimal in command]

	git show 6766e95ba3c84ce262cfaad4d105151ffeb341f4

To find the status of uncommited files in directory

	git status

To find the branches in the repo

	git branch

To check the difference between branches

        git diif branch1...branch2

To find the difference between last version of a file local repo 

	git diff file

To revert back to previous version in local repo

	git checkout file

To remove from the git staging area.[To not tracked to be commited]

	git rm --cached -r .

## Branches

To Create a Branch

	git branch branch_name

To move to another branch

	git checkout branch_name

To push to curent branch

	git push --set-upstream origin branch_name

To push the file

	git push
	
To merge branches

	git merge branch_name
	
 To delete branches

	git branch -d branch_name

## .GITIGNORE

To commit something that is so important and make it not able 
to used by any other

Creat a git ignorr file

	touch .gitignore

Add file names to the gitignore file which to be  not commited 
or uploaded to the repo.
 
