git fetch upstream
git rebase upstream/master
git add "file name"
git rebase --continue

git commit --amend -m "xxx"
git push origin master --force

