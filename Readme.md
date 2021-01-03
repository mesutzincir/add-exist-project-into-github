
create a new git repository in github. for example: add-exist-project-into-github

open command prompt  (run cmd) 

go into project folder which you want to add github in CMD.

run below commands.

1- git init

2- git add . 

2.5 - this step optinal. if you did not set your gut user info before globbaly, you need do it to use  git config --global user.email "your email adresd" and   git config --global user.name "username"

3- git commit -m "first commit"


4-  git remote add origin https://github.com/mesutzincir/add-exist-project-into-github.git

5- git push --set-upstream origin master


After you amde some changes in your project, you need to push them in Github. 

1- git add .

2- git commit -m "your comment for your changes"

3- git push -u origin
