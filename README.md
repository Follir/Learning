git clone git@github.com:<Follir>/coding-interview-university.git
git checkout -b progress
git remote add jwasham https://github.com/jwasham/coding-interview-university
git fetch --all
git add .
git commit -m "Marked x"
git rebase jwasham/main
git push --set-upstream origin progress
git push --force
