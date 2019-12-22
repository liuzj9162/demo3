# demo3
git init
git config (--global/local) user.name "lzj"
git config (--global/local) user.email "liuzj9162@163.com"
git add gitTest.java
git commit gitTest.java -m "change01 dev A"

# Remote push and pull
git remote add origin url
git push origin master
git pull origin master


git clone url
vim gitTest.java
git add gitTest.java
git commit gitTest.java -m "change02 by dev B"

#Version ahead and back
git reset --hard HEAD^
git reset --hard HEAD~2
git reset --hard versionID

#Branch switch and create
git branch -v
git branch feature01
git branch hotfix
git checkout master/feature01/hotfix

#View conflict
git diff

#Create SSH key
ssh-keygen -t rsa -C liuzj9162@163.com




