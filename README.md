hello
check file or document:   ls

check hidden files:    ls -a

first git ko initialize kiya jayta hai uske phle bhi status ko check krte hain 
 
 #git status
  #git init

  now we can add file

  #git add <file name>

  next step commit karna 

  #git commit -m <"message">

  git repositry ko add karenge 

  phle check karo 
  #git remote -v

  if exist then push kr skte ho nhit yye repo location add kkaro

  #git add origin https://github.com/username/reponame.git

  and the push your file 
  push command

  #git push origin main

  set origin

  #git push -u origin main    nextTime run again file push  #git push

  change your origin location

  #git set-url origin https://github.com/username/reponame.git

  and again push command repeat 


if you change your branch 
#git branch checkout <branchName>

create new branch

new branch create kne krne liye ye command hai
#git branch <new branch name> 

#git witch -c <branch name>       ye command chalane pr yadi jo name pass kiya hai apne agar exist karta hai to usme switch ho jaoge nhi to new branch create ho jaegi;

if you should to merge branches app us branch me jao jisme merge karna chahate ho kisi other branch ko

git merge <branch name>

agar galti se file push karne ke baad file direct delete ho jati hai to ye command run karo 

#git add -u

delete commands

#git commit
#git pull origin main
#git rm fileName

yadi file merge ho rahi ho aur ek dusre se conflict kr rhi ho to aap mannualy karo comman use karo {aur jb dusre file se same branch pr push krte hai to apas me file conflict hoti to isko resolve krne ke liye ye command run kr skte ho }

#git pull origin main --allow-unrelated-histories
#git push origin main