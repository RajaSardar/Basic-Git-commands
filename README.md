<b>
<h3>Git Config:</h3>
git config --global user.name "rajasardar"

git config --global user.email "rj.raj@outlook.com"

# Git To list remote branches:
git branch -r

You can check them out as local branches with:
git checkout -b LocalName origin/remotebranchname

#Git Initialize 

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


<h2>Setting up a new Git Repo</h2>

##Create a new repository on the command line

touch README.md

git init

git add README.md

git commit -m "first commit"

git remote add origin git@github.com:RajaSardar/<reponame>.git

git push -u origin master

##Push an existing repository from the command line

git remote add origin git@github.com:RajaSardar/<reponame>.git

git push -u origin master

<h2>JS commands</h2>

anguler port 4200 kill command 

sudo kill $(sudo lsof -t -i:4200)
  
  
<h3>git discard all changes from a branch in local</h3> 
git reset --hard origin/<branch_name>
  
</b>
