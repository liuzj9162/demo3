#demo3
git init
git config (--global/local) user.name "lzj"
git config (--global/local) user.email "liuzj9162@163.com"
git add gitTest.java
git commit gitTest.java -m "change01 dev A"

#Remote push and pull
git remote add origin url
git push origin master
git pull origin master


git clone url
vim gitTest.java
git add gitTest.java
git commit gitTest.java -m "change02 by dev B"
git commit -am "..."

#Version ahead and back
git reset --hard HEAD^
git reset --hard HEAD~2
git reset --hard versionID
git reflog
git log --pretty=oneline

#Branch switch/create/delete/merge 
git branch -v
git branch feature01
git branch hotfix
git checkout master/feature01/hotfix
git checkout -b feature02  === git branch feature02  git checkout feature02
git merge feature  (on master)
git branch -d feature02
git switch -c dev   (创建并切换)
git switch master


#View conflict
git diff

#Create SSH key
ssh-keygen -t rsa -C liuzj9162@163.com




