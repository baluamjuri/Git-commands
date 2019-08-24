# Git-commands

#Clone repository
git clone https://github.com/baluamjuri/Git-commands.git GitCommands
cd GitCommands

#Status of the untracked/unstaged, tracked/staged
git status

#Add or track the files
git add gitcommands.txt
git add *.java
git add 'filename with spaces.txt'

#Make the staged files unstaged
git restore --staged .
git restore --staged *.txt

#Remove file 
rm -f gitcommands.txt

#Commit with message
git commit -m"adding new commands to the notes"

#Push to publish your local commits
git push

#List all files in the repository
ls

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

#To delete a remote branch
git push --delete origin feature/samplebranch

#show all remote branches
git branch -r

#shows all local and remote branches
git branch -a