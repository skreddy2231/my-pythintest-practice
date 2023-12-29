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
"# my-pythintest-practice" 

### create a new repository on the command line --->
echo "# my-pythintest-practice" >> README.md
git init
git add README.md


git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/skreddy2231/my-pythintest-practice.git
git push -u origin master

created origin, check origin in git
git remove -v


----->


# Add a new remote upstream repo that will be synced with the origin repo
-- git remote add upstream <original-repo-url>

# this will fetch data from upstream
-- git fetch upstream

# Navigate to branch
git checkout <branch-name>

