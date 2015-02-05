#cloning  bare repository

 git clone --bare my_project my_project.git

#putting the bare repository to the server

 scp -r my_project.git user@git.example.com:/opt/git

#cloning your repository inside the bare repository

 git clone user@git.example.com:/opt/git/my_project.git

#adding automatic group premission at init

 git init --bare --shared

#generating an SSH key

 ssh-keygen

#setting up the server

 sudo adduser git
 su git
 cd
 mkdir .ssh && chmod 700 .ssh
 touch .ssh/authorized_keys && chmod 600 .ssh/authorized_keys

#creating user keys

cat /tmp/id_rsa.john.pub
ssh-rsa SSH_KEY gsg-keypair

#adding user keys to the authorized keys

 cat /tmp/id_rsa.john.pub >> ~/.ssh/authorized_keys
 cat /tmp/id_rsa.josie.pub >> ~/.ssh/authorized_keys
 cat /tmp/id_rsa.jessica.pub >> ~/.ssh/authorized_keys

#restricting users to only use the git shell

 cat /etc/shells
 which git-shell
 sudo vim /etc/shells


#-------------------------------

touch README.md
touch chptr4_answers.md
git status
git add *
git commit -m "chapter 4"