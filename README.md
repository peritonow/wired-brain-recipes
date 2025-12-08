```
git config --global user.name "unknown"
git config --global user.e-mail "peritonow@gmail.com"
git config --list
git config user.name
git help config
git help 
man git
git config --list --show-origin | grep user.email

git init 
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/peritonow/wired-brain-recipes.git
git push -u origin main

or push existing repisotory
git remote add origin https://github.com/peritonow/wired-brain-recipes.git
git push -u origin main
```

```
git status --short
git diff --staged
git diff --staged --no-renames
git commit -a -m "add new vendor"
git push origin main
// explanation: push changes to origin main branch
```
