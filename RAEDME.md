# Git Basic Commands
git init
git config --global user.name "Harvey2504"
git config --global user.email "atibsamal96@gmail.com"
git config --global core.editor notepad
git config --global --list
mkdir git_samples
echo "new file content" >> test.txt
cat test.txt
notepad test.txt
git add filename
git add .
git status
git log
git commit -m "meaningful message"
git checkout -b feature1
git branch feature1 (creates only)
git branch
git checkout master
git branch -m main (renamed)
git remote add origin https://...
git push origin master
git pull https://
git pull origin master https://
git tag -a dinner
git tag dinner
git tag -a mytag -m "hye"
git tag
git fetch -all
git fetch <branch URL> <branch name>
git fetch <repo URL>
git fetch origin
git clone https://
git rebase mastergit log -1
ls -a :hidden files
ls .git/ :opens .git folder
git push -f
git show -ref master
git diff
git merge (checkout to master and merge)
git branch -d newfeature
git config --global help.autocorrect1 (fuzzy match command)
git add -u (only updated files)
git diff asdfg...sdrtgsxyh (SHA1's)
git diff HEAD~1....HEAD
git diff HEAD~1...
git reset --hard
git reset --soft HEAD~1 (wont remove changes,takes to last commit)
git clean -n (what?)
git clean -f (does)
notepad .gitignore (wont commit those types of files)
git commit -am "sharing" (just for updated files only)
git log --oneline
git log --online | wc -l (counts commits)
gir shortlog
git revert HEAD (also asks for message)
git push --tags
git branch -d bug1234
git branch -D bug1234
git stash
git stash list
git stash pop (removes)
git mergetool
git push origin : rmotebranchname (branch to be deleted)
git push origin v1.0 :  (creates a remote branch with same name)
git push origin v1.0 : v1.0fixes
git push origin --delete myExample

Note:
Always merge and delete the feature branches


# Webhooks (also with ngrok for local sys)

#pull request
#merge tool

# About Maven
POM : Project Object Model

mvn clean

mvn validate

mvn compile

mvn test

mvn package

mvn install

