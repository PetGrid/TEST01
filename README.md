# test

git init - initialized empty git repository in folder
git status - is used to see if a file in part of our repo
git add "filename" - the file becomes staged or added in our repo
git commit -m ""  - adding commits keep track of our progress,changes
git log - see logs
git help or git help --all - to see available options for commands


branch is a new/separate version of the main repository

git branch "branchname"
git checkout "specific branchname" - switched to branch "specific branchname
git checkout -b "branchname" -  it will create a branch "branchname"

using the -b option on checkout will create a new branch, and move to it, if it does not exist


MERGE BRANCHES

git checkout master - to switch to branch master
git merge "branchname" - merge the branchname to master

after merging we can delete branchname
git branch -d "branchname"


push local repository to github
if you have already set up a local git repo, we can push that to github

copy url and paste it in terminal
git remote add origin "the url "

then we are going to push our master branch to the origin url and set it as the default remote branch
git push --set-upstream origin master

git fetch origin - gets all the change history of a tracked branch/repo
                   fetch updates to see what has changed on github


git pull - it is used to pull all changes from a remote repository into the branch you are working on

git push - making the changes to our local git and pushing them to github

remember to first commit and then push


to push our changes to our remote origin 
git push origin


if there is a new branch on github but not in your local git then use a option to see all local and remote branches
git branch -a     
branch -r is for remote branches only

to push branch trom local git repo to github
git push origin "branchname"





