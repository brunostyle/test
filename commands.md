<!-- 1 -->
git init  
<!-- 2 -->
git clone <url>  
git clone --depth <numero> <url>  
git clone --branch <nombre-rama> <url>  
<!-- 3 -->
git config --global --list  
git config --global -e  
<!-- 4 -->
git add <nombre-archivo>  
git add .  
<!-- 5 -->
git restore <nombre-archivo>  
<!-- 6 -->
git commit -m <mensaje>  
git commit -am <mensaje>  
git commit --amend -m <mensaje>  
git commit --amend --no-edit  
<!-- 7 -->
git status  
git status --short  
<!-- 8 -->
git reset --soft HEAD~1  
git reset --mixed HEAD  
git reset --hard HEAD~1  
<!-- 9 -->
git revert <hash>  
git revert --continue  
git revert --abort  
git revert --no-edit <hash>  
<!-- 10 -->
git log  
git log -<numero>  
git log --oneline  
git log --graph  
git log --all  
git log --author=<autor>  
git log --grep=<palabra>  
git log --since=<fecha>
git log --until=<fecha>  
<!-- 11 -->
git shortlog  
git shortlog -se  
<!-- 12 -->
git show  
git show <hash>  
git show --name-only  
git show --name-status  
<!-- 13 -->
git ls-tree -r --name-only HEAD  
git ls-tree -r --name-only <hash>  
git ls-tree -r --name-only HEAD:<nombre-carpeta>  
<!-- 14 -->
git blame <nombre-archivo>  
<!-- 15 -->
git reflog  
<!-- 16 -->
git branch  
git branch -r  
git branch -a  
git branch -v  
git branch -d/-D <nombre-rama>  
git branch -m <nombre-rama>  
git branch -m <nombre-viejo> <nombre-nuevo>  
git branch --merged  
git branch --no-merged  
<!-- 17 -->
git switch <nombre-rama>  
git switch -c <nombre-rama>  
git switch --detach <hash>  
<!-- 18 -->
git merge <nombre-rama>  
git merge --continue  
git merge --abort  
git merge --ff-only <nombre-rama>  
<!-- 19 -->
git rebase <nombre-rama>  
git rebase --continue  
git rebase --abort  
git rebase -i HEAD~<numero>  
<!-- 20 -->
git cherry-pick <hash>  
git cherry-pick --continue  
git cherry-pick --abort  
git cherry-pick --no-commit <hash>  
<!-- 21 -->
git grep <texto>
git grep <texto> -- <archivo>
git grep <texto> HEAD
git grep -i <texto>
git grep -w <texto>
git grep -c <texto>
git grep -n <texto>
<!-- 22 -->
git remote  
git remote -v  
git remote show <nombre>  
git remote add origin <url>  
git remote rename <nombre-viejo> <nombre-nuevo>  
git remote remove <nombre>  
<!-- 23 -->
git fetch <url>  
git fetch --prune  
<!-- 24 -->
git pull  
git pull --ff-only  
git pull --rebase  
<!-- 25 -->
git push  
git push -u origin main  
git push --force  
git push --tags  
git push origin --delete <nombre-rama>
