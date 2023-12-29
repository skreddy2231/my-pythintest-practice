Demo Git Repository

git init
git init git-demo

git add index.html
git status
git commit -m "new html file added"
git status

# remove file
type nul > debug.log
git add debug.log
git commit -m "debug lof added"
git rm deug.log
git status
git checkout -m "removed debug file"
