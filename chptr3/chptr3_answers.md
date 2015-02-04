#creating a new branch

git checkout -b <branch_name>

#transfering to another branch

git checkout <branch_name>

#deleting a branch

git branch -d <branch_name>

#doing a basic merge

git merge <branch_name>

#checking last commt on a branch

git branch -v

#check merged branches

git branch --merged

#check unmerged branches

git branch --no-merged

#updating your local repository

git fetch [<remote> <branch>]

#pushing a branch

git push <remote> <branch>

#pushing your updating a remote branch

git push <remote> <local_branch>:<remote_branch>

#pulling (fetch and merge)

git pull

#rebasing (done after fetch)

git rebase <root_branch>

#-------------------------------

touch README.md
touch chptr3_answers.md
git status
git add *
git commit -m "chapter 3"