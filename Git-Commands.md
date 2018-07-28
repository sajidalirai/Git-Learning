# GIT BASIC COMMANDS

## Create Repositories
create a new repository with specified name
```
git init [project name]
```
clone the existing project and its entire history
```
git clone [url]
```

## Make changes

list all new or modified file to be commited
```
git status
```
show the file differece yet not staged
```
git diff
```
snapshort the file in preparation for versioning 
```
git add [fileName]
```
show the differece between the staged file and the last file version
```
git diff \-\-staged
```

record file snapshorts permanentaly in version history.
```
git commit -m "[descriptive message ]"
```


## Group Changes

list all the branches in the current repository
```
git branch
```
create a specified branch
```
git branch [branch-name]
```
switch to the specified branch and update the working directory.
```
git checkout [branch-name]
```

merge the specified branch history into the current branch
```
git merge [branch]
```
Delete the specified branch
```
git branch \-d [branch]
```

## Review History

list version history for the current branch
```
git log
```

get version history of a file including renaming
```
git log \-\-fellow [file-name]
```

shows the difference between the first branch and the second branch
```
git log [first-branch]...[second-branch]
```

Output the metadata of the specified commit... it require the commit SHA-1 code
```
git show [commit-SHA-1 CODE]
```


## REDO COMMITS
Undo all commits after [commit], preserving changes locally.
```
git reset [commit]
```



## SYNCHRONIZE CHANGES
Download all the history from the repository bookmark
```
git fetch [bookmark]
```

Upload all the local branch commits to Github
```
git push [alias] [branch]
```
Download bookmark history and incorporate changes
```
git pull
```
