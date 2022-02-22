# git-toolbox

### This toolbox contains Zarys common git commands

<img src="https://github.com/zm00622/git-toolbox/blob/main/Git-Explained.png?raw=true">

## Common Git Commands

# Push React App to Master (in Angular you do not have to initialize with git init)

git init

git add .

git commit -m"Place your commit message here"

git remote add origin "https://. "

git push -u origin master

# If having problems with the above commands

git add .

git commit

git push

# Create a New Branch

git checkout -b branch_name

# Switch to a new branch

git checkout branch_name

# Push your branch to the remote repository

git push -u origin branch_name

# Starting on a new branch with a team

First, see which branch you are on.

git remote -v 

Next, create or checkout the new branch (you checkout if the branch already exists. In the example below, Email-Notifications-1 is the new branch name that has already been created in our remote.)

git checkout Email-Notifications-1

Next, make sure your local matches your remote by pulling the remote changes

git fetch

Next, git checkout Email-Notifications-1 again and make sure your terminal has switched to that branch. Your terminal should then say something along the lines of:

Branch 'Email-Notifications-1' set up to track remote branch 'Email-Notifications-1' from 'origin'.
Switched to a new branch 'Email-Notifications-1'

Next,

git add .

Next, 

git commit -m""

Next, git push -u origin Email-Notification-1

# Cloning a Repo

https://blogs.sap.com/2019/07/12/how-to-clone-a-github-repository-to-local-mac-computer/

After cloning a repo, you may have to rename the remote origin stored in git:

git remote set-url origin "https://etc. etc."

# Git Remote Name

git remote -v

# Git Remove Remote

git remote rm origin

# Revert Changes

git revert vs git reset; Reset removes the commit while revert removes the changes but leaves the commit; Revert is safer considering we can revert a revert.

# Force Git Pull to Overwrite Local

https://stackoverflow.com/questions/1125968/how-do-i-force-git-pull-to-overwrite-local-files

# Get a list of remote branches

git branch -r

# Get a list of local branches

git branch

# Current Workflow at my Current Company

1.) We create our own branch and work on our tasks there (branch names are normally named after the Jira issue)

2.) We then test locally

3.) Pull from stage to sync file changes with others

4.) Fix merge conflict if a merge conflict exists

5.) Push to stage (it will then trigger the push to live functionality)

# Cherry Pick

git cherry‑pick 

A powerful command that enables arbitrary Git commits to be picked by reference and appended to the current working HEAD. Cherry picking is the act of picking a commit from a branch and applying it to another.

# List staged and unstagged changes

git status

# Helpful Resources 

**How to Undue Anything with Git**

https://github.blog/2015-06-08-how-to-undo-almost-anything-with-git/

**SmartGit**

https://www.syntevo.com/smartgit/

**Game**

This is an interactive git game played in the terminal. It goes beyond the basics and introduces features like cherry-pick, etc.

https://github.com/git-game/git-game-v2


