ssh-keygen -t rsa -b 4096 -C "@gmail.com"  
cat ~/.ssh/id_rsa.pub
add the key to github acc

Demo to git hub 

First, enter the username and email id by the command, 
git config --global user.name "name"
git config --global user.email "email"

1st create a repository in GitHub and copy the shh/http under the code sub-menu

clone the project in vs using the command:
git clone <link>

add the changes from the working repository to the remote repository by the command,
git add fileName // for a specific file
git add . // for all the files that has been changed

Then commit the changes to remote repository by the command,
git commit -m "commit-msg"

Add orgin,
git remote add orginname sshlink

All the resources can be pulled from the repository by,
git pull orgin branch

git status to check the status like what are about save or the stae of the file.

git push orgin branch

git switch -c branch

git switch branch

