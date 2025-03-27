 Difference between Branch and rebase using git bash
 Create one folder.
Open Git Bash and go to that folder. (cd c:\\....)
git init
git status
touch master1.txt
ls
git status
vim master1.txt
cat master1.txt
cat master.txt
git status
git add .
git status
git commit -m "added master1.txt"
git branch hiray
git checkout hiray
git status
vim hiray1.txt
cat hiray1.txt
cat hiray1.txt
git status Add the file, perform commit operation and check the status.)
git add .
git commit -m "added hiray1.txt"
git status
git log
git checkout master
git status
vim master2.txt
cat master2.txt
git status
git add .
git commit -m "added master2.txt"
git checkout hiray
git status (git meerge complete)
Git Rebase:
 Create on folder say “GitRbase”.
 Open Git bash, go to that folder and initialize git.
cd folder open
git status
touch m1.txt
git add .
git commit -m "added m1.txt"
git log
git branch hiray
git checkout hiray
git status
git log
touch h1.txt
git add .
git status
git log
git checkout master
touch m2.txt
git add .
git log
git checkout hiray
# perform rebase
git rebase master 
git log

