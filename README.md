**--create a new repository on the command line**

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/rtls-net/git-command.git

git push -u origin main



**-- push an existing repository from the command line**

git remote add origin https://github.com/rtls-net/git-command.git

git branch -M main

git push -u origin main

**-- create branch and push to BitBucket  from the command line**

git init

git add *

git commit -m "type message"

git branch -M `<new Branch name>`

git remote add origin https://github.com/rtls-net/git-command.git

git push -u origin `<new Branch name>`



### General Command

git pull -r origin master

