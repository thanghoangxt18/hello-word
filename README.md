git add  : them vao
git commit -m '....' : commit va dat ten cho commit

git log:
git status:
git show:
git diff:

git branch:
git checkout: -- <file>
git reset:
git checkout -b <branch>

 A<---- B
 git merge B
 git branch -D <branch> : xoa

****
 git reset --soft <code of commit>: dua commit ve trang thai truoc khi commit, sau khi add
 git reset --mixed <> :  dua file ve trang thai truoc khi add (unstaged changes:)
 git reset --hard <code of commit>: bo het file da commit cho den commit nay
****
git revert: bo di commit do (han che dung)
 asdfasdfasdfasdfasd
 ***
 .gitignore: dua ten file vao trong file .gitignore thi no se khong commit file do


 *** github
 1.git remote add <https....git>
 2.git push --set-upstream origin master
 3.git push origin master -f : cho push lan dau
 
 ***
 -git congif --global credential.helper "cache --timeout=18000"
 -google "gnome-keyring" "git ssh"

 ***
 git clone
 git push
 git pull
 ***
 Pull request
 1.git checkout
 2.git push origin <branch>
 3.create a pull request on github
 4.review code
 5.merge to master