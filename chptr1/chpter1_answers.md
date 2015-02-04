#to set up account

git config --global user.name "John Doe"
git config --global user.email johndoe@example.com

#setting up editor

git config --global core.editor emacs

#checking up settings

git config --list

#-------------------------------

touch README.md
touch chptr1_answers.md
git status
git add *
git commit -m "chapter 1"