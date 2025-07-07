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
git commit -m [mensaje]
git commit --amend -m [mensaje]
git commit --amend --no-edit
<!-- 6 -->
git log
git log --oneline
git log --graph
git log --all
<!-- 7 -->
git shortlog
git shortlog -se
<!-- 8 -->
git reflog
<!-- 9 -->

<!-- 10 -->
git branch
git branch -r
git branch -a
git branch -v
git branch -d/-D [nombre-rama]
git branch -m [nombre-rama]
git branch -m [nombre-viejo] [nombre-nuevo]
git branch --merged
git branch --no-merged
<!-- 11 -->
git merge [nombre-rama]
git merge --ff-only [nombre-rama]
<!-- 12 -->
git switch [nombre-rama]
git switch -c [nombre-rama]
<!-- 22 -->
git remote add origin [url]
<!-- 24 -->
git push
git push -u origin main
<!-- 25 -->

<!-- 26 -->