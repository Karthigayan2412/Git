Revert Changes
-
Locally
-
git restore file_name
or
git checkout --filename
git status

Staging Directory
-
Commands
-
git reset
git restore --staged
git restore --filenanme

example
-
git log
git add .
git commit -m "Files added"
git status
git reset head~
or
git reset ^head
git restore --filename

Gitignore
-
Avoid unnecessary files to be commited
hidden file

.gitignore 
-
Example:
-
Create a file and add the file name to .gitignore
git add.
git status
git commit -m "Files added"
git push origin master

.gitignore files are not tracked.
