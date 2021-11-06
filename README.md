# get configuration
```
git --version
git config --list
git config user.name
git config user.email
```

# configure user
```
git config --global user.name "AntoineDurand"
git config --global user.email "antoine.durand33@free.fr"
```

# verification
```
git status
```

# delivery
```
git init
git add .
git commit -m "delivery on"
```

# branching
```
git branch
git branch nameOfBranch
git checkout master
git checkout nameOfBranch
git merge nameOfBranch
git branch -d nameOfBranch
```

# log
```
git log
git log -oneline
```

# link
```
git remote add origin https://github.com/adurand33/Landkit.git
git remote -v
```
