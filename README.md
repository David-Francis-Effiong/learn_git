#How I created the 'learn_git' project
**mkdir learn_git** = create a new folder
**cd learn_git** = change directory of that folder
**echo >>third.txt** = add a text file to the folder
**git init** = initialize git
**git add .** = add the text file to the staging area
**git commit -m "adding third-txt"** = commit the file and name it
**git log** = checks the history including the author's details. This is also where I noticed that the default branch is 'master'.
I also added another text file, added it to the staging area, and committed it. I used 'rm' to remove the third.txt file, but it didn't go through. 
**del third.txt** = this synax worked to delete the third text file. I added it to the staging area and commit with the message "removing third.txt"
I checked my log and listed out all global and local configurations using the **git config --global --list** syntax and **git config --local --list**
**git branch** = to check what branch i am using
**git branch -m master main** = change master branch to main
**git remote add origin (https://github.com/David-Francis-Effiong/learn_git.git)** = connect my project to the newly created repo on github
**git remote -v** = confirm my remote repo
**git push -u origin main** = push the completed project to the remote repository
