# Git Commands

### Committing strategies

#### Adding file to the git using git add command
```
git add <filename>
```

[//]: # ()

#### to find the difference in the file
````
git diff <filename>
````

#### How to compare and add or skip the differences.

````
git add -p <filename>
````

#### To make commit using the editor
````
git commit
````

### Branching strategies


##### GitHub FLow 
- very simple, very lean: only one long running branch ("main") + feature branches

##### GitFlow
- more structure, more rules
- long running: "main" + "develop"
- short-lived: feature, releases, hotfixes


### Pull requests

#### Branching: Open new Branch using git cli

````
git branch <branch name>
````


#### Switching between branches
````
git switch <branch name>
````

##### Checking out between branches
````
git checkout <branch name>
````

#### Checking out by creating new branch 
````
git checkout -b <branch name>
````

#### Committing in one commit
````
git commit -m "You can write here your message!"
````

#### Pushing to remote branch
````
git push --set-upstream origin <branch name>
````

### Merge Conflicts

#### Merging to branch 
````
git merge <branch name>
````

#### How to undo a conflict and start over
````
git merge --abort
git rebase --abort
````

### Merge vs Rebase

 





