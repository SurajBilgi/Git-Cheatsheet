## Git-Cheatsheet
My Git Cheatsheet for Reference

***
## Git
#### Version Control System is a tool that helps to track changes in code
#### Git is a VERSION CONTROL SYSTEM.

It is
#### -> Popular
#### -> Free & Open Source
#### -> Fast & Scalable.

***
## Github
#### Website that allows developers to Store and manage their code using git

***
#### 
#### 
#### 
#### .
#### .

#### Types of Files
```
Untracked: New Files that git doesn't yet track
Modified: Changed
Staged: Files ready to commit
unmodified: unchanged
```
***

#### Configuring Git
```
git config --global user.name "MyName"
```
```
git config --global user.email "MyEmail"
```
```
git config --list
```
***


#### Initialize an existing directory as a Git repository
```
git init
```
```
git remote add origin <link>
```
```
# To Verify Remote
git remote -V
```

***

#### Branch Commands
```
git branch
```
```
# To Rename Branch
git branch -M main
```
```
# To Delete Branch
git branch -d old-branch
```

```
git checkout <branch name>
git checkout -b <new branch name> 
```

```

```
***

#### Retrieve an entire repository from a hosted location via URL
```
git clone [url]
```
***


#### Add & Commit
```
# add - adds new or changed files in your working directory to the Git staging area.
git add <file name>
```
```
# commit - it is the record of change
git commit -m "some message"
```
***


#### Push Command
``` Upload local repo content to Remote Repo
git push origin master
```
***


#### Merging Code
```
git diff <branch name>
git merge <other branch name>
```
***


#### Pull Command
```
git pull origin master
```
***


#### Undoing Changes
```
# Case 1: Unstaged Changes
git reset <file name>
```
```
# Case 2 : commited changes (for one commit)
git reset HEAD~1
```
```
Case 3 : commited changes (for many commits)

git reset <- commit hash ->

# get commit hash code from > git logs 
git reset -- hard <- commit hash ->
```
***


#### Tagging
```
git tag -a v1.0 -m "First Release"
git tag
```
***


#### 
```

```
***


#### 
```

```
***


#### 
```

```
***
