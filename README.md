# demo3
git init
git config (--global) user.name "lzj"
git config (--global) user.email "liuzj9162@163.com"
git add gitTest.java
git commit gitTest.java -m "change01 dev A"

git remote add origin url
git push origin master

git clone url
vim gitTest.java
git add gitTest.java
git commit gitTest.java -m "change02 by dev B"

git pull origin master
