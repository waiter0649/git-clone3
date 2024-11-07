echo "# git-clone3-js" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/waiter0649/git-clone3-js.git
<<<<<<< HEAD
git push -u origin master# git-clone3-js
=======
git push origin master 

git remote remove origin
>>>>>>> 561e482c6e10c7f980f2524cc46b6b1d86cb1956
