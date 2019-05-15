# Git-Commands
create a blank repository
open a terminal inside the folder u want to push
$git init
$git config --global user.name "gowshalinirajalingam"
$git config --global user.email gowshalinirajalingam@gmail.com
$git add .
$git commit -m "sdfsdf"
$git remote add origin https://github.com/gowshalinirajalingam/repo-name.git
git push -u origin master

#check the origin repository that has been set to the local git folder
$git remote -v            

#change the origin repository that has been set to the local git folder
$git remote set-url origin https://github.com/gowshalinirajalingam/repo-name.git

#list all branches
$git branch -a

#Checkout the branch you want to use. 
$ git checkout <feature_branch>

#Confirm you are now working on that branch: 
$ git branch.

#Delete brance from origin
git push <remote_name> --delete <branch_name>


