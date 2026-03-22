# Breath
Github Task

#What is Version Control?

Version control, also known as source control, is a system that records changes to files and code over time, allowing developers to track history, revert to previous states, and collaborate seamlessly. It enables multiple developers to work on the same project simultaneously without overwriting each other's work by managing branches and merging changes. 

#Difference Between git and github

i. Git is a tool, while github is a platform
ii. Git is a version control system used to track code      changes locally while github is a cloud platform used to   host git repositories online 
iii. Git could work offline while github requires internet for remote operation.
iv. It is installed on your computer, while github could be installed as an app, but could be accessible via browser. 

#Three Github alternatives

i. Gitlab
ii. Bitbucket
iii. Gitea

#Difference between gitfetch and gitpull

*GIT FETCH is a "safe" operation that retrieves the latest commit history and files from the remote repository but keeps them separate from your local working files, While
GIT PULL combines the functionality of two commands: git fetch followed by git merge.
*GIT FETCH updates your local copy of remote-tracking branches (e.g., origin/main), not your actual working branch (e.g., main). WHILE
GIT PULL fetches the remote content and immediately tries to integrate it into your current local branch.

#Git rebase

Git rebase is used to move or combine a sequence of commits onto another base branch. It keeps a cleen project history. 
COMMAND:
git rebase main

#git cherry-picks

Git cherry-picks allows you to pick a specific commit from one branch and apply it to another branch
COMMAND: 
git cherry-pick <commit-hash> 