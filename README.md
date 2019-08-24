# Git-commands

#Clone repository
git clone https://github.com/baluamjuri/Git-commands.git GitCommands

#Status of the untracked, tracked, staged and unstaged files
git status

git stash
git pull

#If any conflicts then resolve it
git stash pop 

commit from tortoise git

git push

#to uncommit the changes
git reset --soft HEAD~ 

#to untrack a tracked file
git rm --cached filename 

#To switch to branch
git checkout redsky_UFE18R8_sprint3

#To create a branch
git checkout -b feature/feature_redsky_UFE18R8_sprint3_unittest redsky_UFE18R8_sprint3

git checkout -b feature-security-usermgmt-restendpoints

#To delete a branch locally
git branch -d feature-security-usermgmt-restendpoints

#show all remote branches
git branch -r

#shows all local and remote branches
git branch -a
