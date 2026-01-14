# GitSetUp

git init
git add .
git commit -am "initial commit"
git remote add origin  https://github.com/arshahrear30/Task-Manager.git
git remote -v
git push origin master
git fetch origin main:tmp
git rebase tmp
git push origin HEAD:main
