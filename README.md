# GitSetUp

git download and Connect with Android studio by Token 

https://git-scm.com/

git init
git checkout -b main
git add .
git commit -m "initial commit"
git remote add origin 'https://github.com/arshahrear30/miniexel.git'
git push -u origin main



git checkout -b main
git push -u origin main

Detached HEAD থেকে বের হবে
Local main branch তৈরি হবে
Future এ শুধু git push লিখলেই হবে



Everyday code update workflow
git add .
git commit -m "your message"
git push



2nd bar onek somoy error hoy tai : 
git config --global credential.helper manager-core

er por onek somoy error vavey set hoi tai :
git config --global --unset credential.helper // eta maney purber setup reset hoy ..
git config --global credential.helper store


error rejected (fetch first)
git pull origin main
git push



error text : 
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
Solution : 
git pull origin main --allow-unrelated-histories   // এটা দিলে ফাইলগুলো নষ্ট হয়ে যায় কারণ দুইটা ফাইল একসাথে করার চেষ্টা করে



