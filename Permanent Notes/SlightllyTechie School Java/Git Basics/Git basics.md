#Untitled
Created: 2024-07-23 16:35

**The .git Folder**

The .git folder is what tracks everything you do in your repository. 
the commits are stored in subfolders using their first 2 letters to create them. 

using git cat-file <commit SHA> you can trace back and get the project of a repo using the commit the user made.

git merge = after branching away from trunk or your current branch to create new content in your branch you use git branch <source branch> to merge into the current branch
but if the trunk or current branch has also made changes then trying to merge into it will cause the merge commit and not a fast forward commit. 

git add . = adds all files in the repo to the commit 
git add<file_name> = adds jus the file with the changes to the commit.

git push = pushes the code from the commit to github.

git rebase = changing the base of the commit to the current commit. it will bring all the commits to the branch you are rebasing on.


**COMMAND FOR CHANGING DIRECTORIES TO WINDOWS OBSIDIAN**
"cd /mnt/c/Users/admin/OneDrive/Documents/Obsidian\ Vault"

GIT REMOTE
git remote it does not necessarily mean a repo that can be accessed over the internet. it could be local too. it just means a copy of your repo at a different location be it another computer or a directory. 

FORKING A PROJECT
copying a project into your local space.

after you do a git fetch you don't have to do a git pull again cos you have already updated your refs so you just do git merge
