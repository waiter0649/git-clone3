echo "# git-clone3-js" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/waiter0649/git-clone3-js.git
git push origin master 

git remote remove origin
