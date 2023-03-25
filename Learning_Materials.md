### To initiatize a repository with git
```
git init
```

### To view changes in the repository and commits
```
git status
```

### To track a file and put it into the staging area
```
git add fileName
```
### To clone a repository from github
```
git clone https://github.com/username/RepositoryName.git
```

### To commit the changes from staging area to local
```
git commit -m "some meaningful message for the commit"
```

### To push the committed changes to Github
```
git push
```

### To push another branch to origin
```
git push -u origin branchName
```

### To push an existing repository
```
git remote add origin https://github.com/username/RepositoryName.git
git branch -M main
git push -u origin main
```

### To view all the commits in the repository
```
git log
```

### To go to some commit or branch
```
git checkout hashcode
```
At hashcode write the hashcode of that commit or write the branch name

### To make a branch
```
git branch branchName
```
You need to checkout to the new branch to go to the newly made one

### To make a branch and at the same time switch to that branch
```
git checkout -b branchName
```

### To merge a branch to the branch you are in
```
git merge branchName
```
This will merge the branchName branch to the branch from where you run this command

### To make .gitignore file
```
touch .gitignore
```
Add the names of the files or folders that you want the git to ignore them

### 
