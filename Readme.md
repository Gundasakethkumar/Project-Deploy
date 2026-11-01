git commit -m "modified the signup functionali" 
git commit -m "modified the login and signup functionality"


Feat: if you're working on any feature or user story commit msg should be add in this way
Fix: when working on fix
Docs: when you're working on the docs 
refractor: refactoring the whole functionality 
test: just testing the functionality with dummy data 
perf: to increase or decrease the performance 

## Branches 

main/master - we will create the branch from the out the of existing branch 
list all branch - git branch
creating the new branch 
step 1 - create a branch - git branch <branchname> , git branch <branchname><source-branch>
step 2- switch to the branch - git checkout <branchname>

step 1 + step 2 = git checkout -b <branchnamr>, git  checkout -b <branchname><source-branch>
### Modern way of creating branches 
-git switch <branchname>
-git switch -c <branchname> or -git switch -c <rbanchname> <sourcebrance> (directly created the branch and checkout to it )
#######

#### Branch naming 
User story / Feature - feature/US-1001-Add-To-Cart-Functionality
Bug --- bugfix/Bug-3434-Fix-Order-Page
Hotfixes - hotfix/adding-columns-to-reports
Release - release/feature-name-DDMMYYYY

#### connect local repo with remote repo 

git remote add origin(name of the remote) (remote URL) https://github.com/Gundasakethkumar/Project-Deploy.git

git push origin <branchname> (pushing the master branch into the origin repo)
    