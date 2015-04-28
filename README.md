This is just my git cheat sheet.


```
NEW REPO:
pico README.md
git init
git add README.md
git add .
git commit -m "first commit"
git remote add origin https://github.com/lleevveell66/<MY_REPO_NAME>.git
git push -u origin master

NEW BRANCH:
git branch
git checkout master
git checkout -b logging
git commit -a -m 'added simple local log file'
git push -u origin logging
git branch

MERGE BRANCH:
git checkout master
git merge logging
git push -u origin master
```
