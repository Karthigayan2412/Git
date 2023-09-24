Git Rebase
-
Reapply commits on top of another base tip

git commit -a -m "files added"
modify the file and execute the above command which is same as

git add .
git commit -m "Files modified"

Apply rebase to squash the commit
-
git rebase -i Head~4
Editor will be displayed, you can select the required option and save it.

example:
-
squash
pick
