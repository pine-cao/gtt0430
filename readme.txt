this a project for signing.
20210424

more files test
add again in branch

time log
move pc to here
cominfo

20210426 monday

abc123456

add some commands using in git:
git init
git add .
git commit -m "change text"
git status
git diff
git log
git log --pretty=oneline
git reflog
git reset --hard ID
git checkout -- filename
git reset HEAD filename
git rm filename

#ssh-keygen -t rsa -C "youremail@example.com"
//add a public key in remote account of github;
git remote add origin git@github.com:pine-cao/gtt0430.git
git push -u origin master
git push origin master

git config --global user.email "you@example.com"
git config --global user.name "Your Name"
git clone git@github.com:pine-cao/gtt0430.git
git clone https://github.com/pine-cao/gtt0430.git
git://
https://

<<<<<<< HEAD
//conflict branch in diff branch;first fix branches,than add and commit;
git branch
git branch dev //create a branch
git checkout dev //switch to branch
=
git checkout -b dev //create and switch to a branch
git checkout master
git merge dev
git branch -d dev
>>>>>>> dev

git merge --no-ff -m "merge with no-ff" dev // no fast forward model
git log --graph --pretty=oneline --abbrev-commit
git restore --staged filename
git log --graph --pretty=oneline

//stage; branches;
//change tracks
//change trancks again.
<<<<<<< HEAD
//branch learn master 2021-0512
=======
//branch learn dev 2021-0512
>>>>>>> dev
//branch learn master and dev merge fix 2021-0512
//branch dev2 --no-ff, no fast forward; git merge --no-ff -m "no fast forward merge" dev2

//fast git:
https://github.com/pine-cao
https://github.com.cnpmjs.org/pine-cao
https://hub.fastgit.org/pine-cao

//bug branch
git checkout dev
//doing work here,but not finished.
git stash
git checkout master
git checkout -b issue101
//edit something
git add filename
git commit -m "fixbug in 101"
git checkout master
git merge --no-ff -m "merged bug fix from branch 101" issue101
git branch -d issue101
git checkout dev
//want to work in dev branch,from the beginning.
git status
git stash list
git stash apply stash@{0}
git stash drop
git stash pop
//pop from the stash.and work again.

//add a new feature in branch
git checkout dev
git checkout -b newfeature
git add .
git status
git commit -m "add a new feature"
git checkout dev
//do not merge it ,delete newfeature branch
git branch -d newfeature
//error:the branch newfeature is not fully merged.
git branch -D newfeature
//deleted branch newfeature


