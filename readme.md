## Hello Git!

- create a new repository on the command line
```git init```
- create a new file
```touch readme.md```
- add file to staging area
```git add readme.md```
- commit file to repository
```git commit -m "Initial commit"```
- commit and add file in one command
```git commit -am "Initial commit"```
- check status of repository
```git status```
- check commit history
```git log```
- check commit history in one line
```git log --oneline```
- check commit history in one line with graph
```git log --oneline --graph```
- check commit history in one line with graph and all branches
```git log --oneline --graph --all```
- add remote repository
```git remote add origin <URL>```
- push to remote repository
```git push -u origin main```
- pull from remote repository
```git pull origin main```
- create a new branch
```git branch feature```
- switch to the new branch
```git checkout feature```
- create branch from main
```git branch developer main```
- this is edited by git feature branch
- to merge the main branch into the <branch name> ex: feature branch 
```git merge main```
- reset soft and hard ```git reset <commite-hash>``` or ```git reset --hard <commit-hash>``` 
- Revert command ```git revert <commit-hash>```
- Rebase command ```git rebase <branch-name>```

[//]: # (test1)
[//]: # (test2)