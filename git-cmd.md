# Git Commands

## Help
git help config

## Track local files on directory

e.g local-Repo

1. cd local-Repo
2. git init .git directory created, contains everything
   related to repository.
3. to stop tracking directory: rm .git
4. git status
5. touch .gitignore - list files to be ignored -text file
   wild cards work /*.txt srl .
6. *add files to stagging areas - git add -A
7. git status
8. git commit -m "message"
9. git log
10. git reset [file] - remove committed file git reset remove all commits

## Clone from remote repository

1. git clone <url> <where to clone> can be local
2. git remote -v lists information: location srl.
3. git branch -a local and remote
4. make change to file
  - git diff : shows changes
- git commit -m "message"
- to push : git pull origin master
- git push -u origin master

## Workflow with Branches
1. git branch <name> ie. git branch dog
2. git branch - show branch working on
3. git checkout <name> ie git checkout dog
4. git add -A
5. git commit -m "message"
6. git push -u origin dog
7. git branch -a
8. merge branch with master
9. git checkout master
10. git pull
11. git --merged - show merged branches
12. git merge dog - merge change in master branch
13. git push origin master
14. git branch --merged - shows merged
15. git branch -d <name> git branch -d dog
16. git push origin --delete <name> git push origin delete
    dog
17. git branch -a









