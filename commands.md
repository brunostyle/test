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
git log
git log --oneline
git log --graph
git log --all
<!-- 9 -->
git shortlog
git shortlog -se
<!-- 10 -->
git blame [nombre-archivo]
<!-- 11 -->
git reset --soft HEAD~1
git reset --mixed HEAD
git reset --hard HEAD~1
<!-- 12 -->
git revert [hash]
Esto estas mal
<!-- 13 -->
git show
git show [hash]
git show --oneline --name-only
git show --oneline --name-status
<!-- 14 -->
git reflog
<!-- 15 -->
git ls-tree -r --name-only HEAD
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
git merge [nombre-rama]
git rebase --abort
git rebase --continue
git merge --ff-only [nombre-rama]
<!-- 18 -->
git rebase [nombre-rama]
git rebase --abort
git rebase --continue
git rebase -i HEAD~[numero]
<!-- 19 -->
git cherry-pick [hash]
<!-- 20 -->
git switch [nombre-rama]
git switch -c [nombre-rama]
<!-- 22 -->
git remote add origin [url]
<!-- 24 -->
git push
git push -u origin main
<!-- 25 -->

<!-- 26 -->