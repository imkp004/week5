# Week5 Lab
Second commit through the git


Testing - This is only for the test branch, just an example



Git Basics commands


for new project first create a folder for project in your computer
then also create the repo in the github same name. Then run commands

git remote add origin <link of the repo>   - to connect this project to github
git remote -v   - To check the repo your project is connected to on github

now anything you push to gihub it will shown all the commits in github, in the sane repo


git init  -  To initilize git in the folder now it will be a repo.
git status  - To check the status of the repo for ex: modified file, untracked file, staged file
git add <filename> or git add .  - To stage the file for commiting, this is first to commit
git commit -m "message"  - To commit the staged changes and with the short message

git clone <link from github>   - To get the copy of the project from the github


git branch  - To check which branch of the projwct we are working in.

branching is like if there is project and different teams are working on it
they take their own copy of the main branch and work in their team. So, now if 
we have frontend, and backend teams they create their own branch from the project 
and start working in it so whatever commits frontend makes will go in the 
frontend branch not the backend branch or main branch. Imagine a tree having branches
which are offset of main branch.

general workflow for git on projects:
first creating github repo
clone it to local computer
edit it the file 
add it to the staging area
and commit it will the short message
finally push it to github



Branch commands:

git branch  - To check which branch we are working on
git branch -M <branch-name>  - To raname the branch
git checkout <branch-name>   - To jump to the diffrent branch

git checkout -b <new-branch-name>  - To create new branch and be on i

git branch -d <branch-name>  - To delete the branch. but you can't be on the branch and delete
                               you have to be on different branch to delete it. 
                         

git diff <branch-name>   - To check differene between the two branches
git merge <branch-name>  - To merge two branches and make it one


Now comes Pull request.
if lot of people wokring on the same project and they want to merge their project with
the main branch so they do a pull request so that the person who is the owner of the project 
or owner of the main branch he will review the code if its good then he will merge the it
with the main branch.

git pull origin <branch-name>


git reset <file> or git reset   - To undo the staged files 

git reset Head~1   - To undo the commit and it will be back at stating area.
git reset --hard HEAD~1   - To undo the changes and commit. This makes your branch look exactly like it did before the last commit.


git log  - To get the history of commits made with description and everything.
