# Git Commands

## Initialization
- `git init`
- `git config --global user.name "Ravindra"`
- `git config --global user.email "ravindrasarade@gmail.com"`

## Repository Status
- `git status`
- `git branch`
- `git branch -a`
- `git log`
- `git reflog`
- `git show-ref master`
- `git log -2`

## File Operations
- `git add .`
- `git commit -m "First commit for Test"`
- `git commit -m "Input name and say Hello"`
- `git commit -m "second commit to add loop"`
- `git commit -m "Test commit"`
- `git rm --cached testfile.txt`

## Tagging
- `git tag "my-first-tag"`
- `git tag "my_first_tag"`
- `git tag -a "My-first-annotated-tag" -m "This commit is related to Second Production release"`
- `git tag "First Hello tag"`
- `git tag -a "First annotated tag for hello.py"`
- `git tag -a "First-annotated-tag-hello-py"`
- `git tag "second-tag-hello-py"`

## Cloning and Fetching
- `git clone https://github.com/mohit264/git_marathi_0824`
- `git pull`
- `git fetch`
- `git clone git@github.com:mohit264/git_marathi_0824.git`

## Branch Management
- `git checkout -b dev`
- `git switch git_marathi_0824/`
- `git switch br git_marathi_0824/`
- `git checkout master`
- `git checkout main`

## Viewing and Manipulating Files
- `git cat-file -p "my-first-tag"`
- `git cat-file -p "my_first_tag"`
- `git cat-file -p "First-annotated-tag-hello-py"`
- `git cat-file -p b5a94bccd9b8eb4b7c50b36cccc845faafe5a636`
- `git cat-file -p 1dba9bbea68752b1412e4da9bc3a2286cb0ace89`

## Miscellaneous
- `pwd`
- `ls`
- `ls -a`
- `clear`
- `echo "Last day of git class" > Ravindra.txt`
- `ssh -T git@github.com`
- `ssh-keygen -t rsa -b 4096 -C "ravindrasarade@gmail.com"`
- `mkdir 90DaysChallenge`
- `touch testfile.txt`
- `vim testfile.txt`
