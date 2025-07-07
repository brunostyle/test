<!-- 1 -->
git init
<!-- 2 -->
git clone [url]
<!-- 3 -->
git config --global --list
git config --global -e
<!-- 4 -->
git add .
<!-- 5 -->
git restore .
git restore [nombre-archivo]
<!-- 6 -->
git commit -m [mensaje]
git commit --amend -m [mensaje]
git commit --amend --no-edit
<!-- 7 -->
git status
git status --short
<!-- 8 -->
git reset --soft HEAD~1
git reset --mixed HEAD
git reset --hard HEAD~1
<!-- 9 -->
git revert [hash]
<!-- 10 -->
git log
git log -[numero]
git log --oneline
git log --graph
git log --all
<!-- 11 -->
git shortlog
git shortlog -se
<!-- 12 -->
git show
git show [hash]
git show --oneline --name-only
git show --oneline --name-status
<!-- 13 -->
git ls-tree -r --name-only HEAD
<!-- 14 -->
git blame [nombre-archivo]
<!-- 15 -->
git reflog
<!-- 16 -->
git branch
git branch -r
git branch -a
git branch -v
git branch -d/-D [nombre-rama]
git branch -m [nombre-rama]
git branch -m [nombre-viejo] [nombre-nuevo]
git branch --merged
git branch --no-merged
<!-- 17 -->
git switch [nombre-rama]
git switch -c [nombre-rama]
git switch --detach [hash]
<!-- 18 -->
git merge [nombre-rama]
git merge --abort
git merge --continue
git merge --ff-only [nombre-rama]
<!-- 19 -->
git rebase [nombre-rama]
git rebase --abort
git rebase --continue
git rebase -i HEAD~[numero]
<!-- 20 -->
git cherry-pick [hash]
git cherry-pick --abort
git cherry-pick --continue
git cherry-pick --no-commit [hash]
<!-- 21 -->
git stash
<!-- 22 -->
git grep
<!-- 23 -->
git remote
git remote -v
git remote show [nombre]
git remote add origin [url]
git remote rename [nombre-viejo] [nombre-nuevo]
git remote remove [nombre]
<!-- 24 -->
git fetch [url]
<!-- 25 -->
git pull
git pull --ff-only
git pull --rebase
<!-- 26 -->
git push
git push -u origin main
git push --force