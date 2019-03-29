git init
ls -ltrha .git
git status
.
touch test.html
git add 'test.html'
git add "test*"
git add -A
git commmit -m 'add test.html to git'
.
git log
git diff HEAD
git diff --staged
.
git reset test.html
git checkout --test.html
.
git branch
git branch sencondBranchName
git checkout sencondBranchName
git merge sencondBranchName
git branch -d sencondBranchName
.
git clone "github URL"
git push origin master
git pull origin master
.
git remote
git remote add origin http://github url
git show commit_hash_code
.
git tag -a v2.0 -m 'message'
git tag -a v1.8 d2234354fg
git tag -l "v*"
git show v1.8
git push origin --tags
.
git help blame
git blame test.html
git blame test.html -L8,10
.
git bisect start
git bisect bad
git log
git bisect good 22rjkrkfej4
