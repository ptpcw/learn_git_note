# learn_git_note

## Git command

git status\
git add . or git add filename\
git commit -m "message to be added" -m "another message to be added"\
git push origin master

git config --global user.email "user@email"\
git config --global user.name  "github username"

git branch --List all branches\
git checkout -b "new branch name" --Create new branch\
git checkout "branch name"        --Switch to branch\
git diff "branch name"\
git branch -d "branch name"        --Delete branch\

git reset\
git log\
git reset --hard "log number" 


## VScode

Use code_1.61.2-1634656828_amd64.deb on ubuntu 20.04

## ssh key

ssh-keygen -t rsa -b 4096 -C "username@email"

copy the content of public key, e.g. ****.pub

## put public key into github
1. In github webpage, got to "Settings" and click "SSH and GPG keys"
2. Click "New SSH key", fill-in "Title" and past the xxxx.pub key into th box of "Key"!

## Local Development

1. Open index.html in your brower.


## Solve "This branch has conflicts .." before mergen pull request

https://github.com/githubteacher/github-for-developers-sept-2015/issues/648#issuecomment-144488223 

or use VScode editor:
options are shown after entering the git merge "branch-name" command 
