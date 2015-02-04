#check staging status/ file status/ branch status etc.

git status

#add files for staging

git add <file>

#remove files from staging

git rm <file>

#reset file to last version

git checkout -- <file>

#creating a commit (non-interactive -- better)

git commit -m "<commit description>"

#checking staged and not staged diffs

git diff [--cached]

#moving/renaming files (a rare thing to do in the command line)

git mv file_from file_to

#view commit history

git log [-p --stat --since, ..]

#undo a latest commit

git commit --amend

#---------remote commands--------#

#cloning

git clone <link_to_repository>

#pushing

git push origin master

#updating (unmerged)

git fetch [remote-name]

#updating (auto-merge)

git pull


#-------------------------------

touch README.md
touch chptr2_answers.md
git status
git add *
git commit -m "chapter 2"