# Git-Course
For Git Course created by me

## Project Notes
These commands will be used frequently to be a professional in github

1 - git status (for checking the status of the file in your local repo)
### this is the staging area that we are checking the status of the files whether they are staged or not.

to unstage a file: git reset head <the file name>

### from the staging to do commit to the local repo 
git commit -m "the message you want to write."

### to know all the branches of the reop
git branch

### to push to the remote repo
git push REMOTENAME BRANCHNAME

### to know the remote name
git remote -v

### pulling changes
git pull REMOTENAME

### to get the configuartion available
git config -l

### how to deal with the public keys
ssh-keygen -t rsa -b 4096 -C "the email you want"
to test test the SSH key
ssh -T git@github.com