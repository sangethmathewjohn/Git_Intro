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
