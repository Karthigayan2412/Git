Fork
-
Copy the one account github repository to other account repository.
which requires authentication

Colloborator
-
settings -> Manage access -> who has access -> Manage colobarator -> invite users

user will recieve an email to accept the invite.

Which will avoid creating the pull request everytime, also you need to fork the repository prior to add user as a collaborator.

Protect Branch
-
code -> settings - > Branch protection Rule -> Branch protection Rule -> Protect Matching Rule -> Select the required rule -> Create

Once the rule is created, whenever any commit is done, new branch is created and approval is required to merge the change.

Tag a Commit
-
Reference to specific commit
Point in history that is used for a version(ie. V.01)

git tag
git tag v1.0
git log
git status
git push origin v1.0

git tag -a v1.1 "Commited the change" -m
git log
git push origin v1.1

Pro account required to use Branch protection
-
