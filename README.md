<b>
git config --global user.name "Raja Sardar"

git config --global user.email raja@theorexlabs.com

git init

git clone /path/to/repository

git clone username@host:/path/to/repository

git add <filename>

git add *

git commit -m "Commit message"

git commit -a

git push origin master

git status

git remote add origin <server>

git remote -v

git checkout -b <branchname>

git checkout <branchname>

git branch

git branch -d <branchname>

git push origin <branchname>

git push --all origin

git push origin :<branchname>

git pull

git merge <branchname>

git diff

git diff --base <filename>

git diff <sourcebranch> <targetbranch>

git add <filename>

git tag 1.0.0 <commitID>

git log

git push --tags origin

git checkout -- <filename>

git fetch origin

git reset --hard origin/master

git grep "foo()"


Setting up a new Git Repo

##Create a new repository on the command line

touch README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:alexpchin/<reponame>.git
git push -u origin master

##Push an existing repository from the command line

git remote add origin git@github.com:alexpchin/<reponame>.git
git push -u origin master

</b>
