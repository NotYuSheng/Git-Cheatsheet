# GitHub-cheatsheet

## Configure username & email
```
git config --global user.name "usernameHere"
git config --global user.email "emailHere"
```

## Store credentials
```
git config --global credential.helper store
git pull
```

## Initialize
```
git init
```

## Branch
```
git branch -m branchNameHere
```

## Adding files
```
git add *
git commit -m "commentHere"
git branch -M main
git remote add origin https://github.com/usernameHere/repoNameHere
git push -u origin main
```

## Subsequent adding files
```
git add *
git commit -m "commentHere"
git branch -M main
git push -u origin main
```

## Unstage (remove from commit before pushing)
```
git restore --staged fileNameHere
```

## Clone
```
git clone https://github.com/usernnameHere/repoNameHere.git
```
