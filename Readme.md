#Git Version<br>
`git --version`
<br><br>

#Git Config<br>
```
git config --global user.name"example"
git config --global user.email"example@yahoo.com"
```
<br><br>
#Git initilization<br>
`git init`
<br><br>
#Git add<br>
```
git add [filename]
git add --a <!--All directory & Subdirectory-->
git add . <!--All Subdirectory-->
```
<br><br>
#Status
<br>
```
git status
git status -short
```
<br><br>
#Unstage<br>
`
git rm --cached [filename]
`
<br><br>
#Restor<br>
`
git restore [filename]
`
<br><br>
#Delete commit
<br>
```
git reset --soft HEAD^
git reset HEAD^
git reset --hard HEAD^
git revert [commit_id]
```
<br><br>
#About commit
<br>
```
git checkout [commit_id]
git show [commit_id]
```
<br><br>
#Log
<br>
```
git log
git log --oneline
```
<br><br>
#Branching
<br>
```
git branch
git branch a
git checkout a
git checkout main/master
```
<br><br>
#Mergeing
<br>
```
git branch
git branch a<!--Create a new branch-->
git checkout a<!--Switch to new branch-->
git checkout main/master
git merge a
```
<br><br>
#Local to remote connection<br>
```
git remote add origin [link]
git pull
git clone [link]
git push -u origin main/master
```
<br><br>
