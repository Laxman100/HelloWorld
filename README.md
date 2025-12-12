echo "# Practice" >> README.md
git init
git add README.md #for example only 
git add . for all all files 
git status 
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Laxman100/HelloWorld.git
git push -u origin main # if u get fetal error use master instead of main

Note: befor push your changes pull others changes first otherwise files get deleted

Cheatsheet:
git init
git clone <url>
git status
git add <file>  | git add .
git commit -m "msg"
git branch / git branch -d
git checkout <branch> | git checkout -b <branch>
git switch <branch>
git merge <branch>
git rebase <branch>
git fetch
git pull
git push
git stash
git log --oneline --graph --decorate
git diff
git reset --hard
git revert <sha>
git reflog
