# test
cd test1
git init
touch favethings.html
touch favethings.css
ls
open favethings1.css
open favethings1.html
git add favethings1.css
git add favethings1.html
ls
git commit -m "added favethings.html and .css"
git branch add-css
git checkout add-css
touch See1.gif
touch Cuilverse1.png
git add Culverse1.png
git add See1.gif
ls
git commit -am "added pictures for CSS"
git branch
git merge --squash add-css
git remote add origin https://github.com/MichonGG/test.git
git push -u origin master
