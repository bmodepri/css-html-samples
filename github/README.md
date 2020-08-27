# GitHub basic commands

## Clone the repository:
git clone https://github.com/gabrielaacha/zamagana_synth

## Create a new branch:
git checkout -n <YourName>
e.g.
git checkout -n marcelo

## List branch(es) (usually the branch that you are using has a "*"):
git branch

## Access a branch:
git checkout <YourName>
e.g.
git checkout marcelo

## Confirm what branch you are:
git branch

## Update your branch with the master branch:
git pull origin marcelo

## Abort merge:
git merge --abort

## Update your branch:
git add .
git commit -m "your comment..."
git push origin marcelo

## Update your branch with a specific file:
git add filename.html
git commit -m "your comment..."
git push origin marcelo

## Update you local master branch:
git checkout master
git pull

## Update your local branchs with master branch data and update remote branches:
git checkout <yourbranchname>
git merge origin/master  
git push origin <yourbranchname>