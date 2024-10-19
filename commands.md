#This command initializes a new Git repository in the current directory.
git init

#Add the README.md file to the staging area

git add README.md

#Commit the staged files

git commit -m "first commit"

#Rename the default branch to "main"
git branch -M main

#Add a remote repository

git remote add origin https://github.com/samirpandey65/git-for-devops.git


#Push the changes to the remote repository

git push -u origin main

