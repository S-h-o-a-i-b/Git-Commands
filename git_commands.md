# Some Usefull Git Commands
-----

### New Folder Create:
```
mkdir folder_name
```

### Delete Folder:
```
rm -r folder_name
```


### Create New file:
```
touch file_name
```
### Delete file:
```
rm file_name
```
### See all file:
```
ls
```

### See all file and also hiden file:
```
ls -a 
```

### Present Directory:
```
pwd
```
### Change Directory
```
cd folder_name
```
### Back from present folder:
```
cd ..
```
### Add user-name in Git:
```
git config --global user.name "your name"
```

### Add Email in Git:
```
git config --global user.email "your Email"
```

### Check Config in Git:
```
git config
```

### Check Username:
```
git config user.name
```

### Check Email:
```
git config user.email
```

### Git initialize:
```
git init
```
### Git Status check:
```
git status
```
### Git Add:
```
1. git add "file_name"
2. git add . 
[using . for adding all files in git]
```
### Git Restore :
```
git restore --staged <file_name>
```
### Git Restore From modification:
```
git checkout file_name
```
### Git ignorefile:
```
touch .gitignore
[in igore file you add file name]
```
### Git Commit:
```
git commit -m"write any message here"
```
### Commit History check:
```
1. git log
2. git log --oneline
```

### Go a indivisual commit:
```
git checkout commit_id
```


### Check Indivisual Commit:
```
git check commit_id
```
### check Indivisual Commit IN details:
```
git show -v commit_id
```
### Git add and commit together:
```
git add file_name && git commit -m"message"
```
### Add local git to Remote repository
```
git remote add origin github_repo_link
```
### Check the remote server is attached or not
```
git remote
```
### Git push to Remote Repository:
```
git push -u origin link
 [here u add github repository link and you use any name instead of origin]
```
### Git Pull to a Remote Repository:
```
git pull origin
```
### Clone Remote Repository:
```
git clone link
[here you add github repository link]
```
### Check Branch:
```
git branch
```
### Branch name change :
```
git branch -m main
```

### Create new Branch:
```
git branch branch_name
```
### Delete a Branch:
```
git branch --delete branchname
```


### Replace main branch to new branch and vice versa:
```
git checkout branch_name
```

### Create and Replace Together:
```
git checkout -b branch_name
```

### Git Merge from one branch to Main Branch:
```
git merge branch_name
```


