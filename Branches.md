#GIT Branch
-
General work flow

SCM -> Build -> testing -> Artifacts -> Deployment -> Build
-
General deployment
-
Testing -> QA -> Production

Strategy:
git branch 
-
generally branch is master which we can check through 'git master' command
*- represents current branch
create a new branch using git branch testing - creates a new branch named testing which has the snapshot of master files.
switch to branch using 'git checkout testing'
git branch - command to confirm which branch you are in

Merge the changes which are present in sub-branch using 'git merge test' this can be executed from master branch.

prior to this..
- 
once you 'git checkout test'
modified the files
git add .
git commit -m "file2 added"
git push origin test

once the above done, we will able to merge from master.
git merge test
git status

git checkout -b 'branch name' - which create a branch and switch to branch as well.

Branch Creation
-
Create a new branch in github just type in branch box.
once branch is created switch to default branch to newly created branch
generally, master will be default
change the default branch to newly created branch, delete the master branch if not required.


