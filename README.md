Complete Command Sequence
1)mkdir Git_Lab
2) cd Git_Lab
3) git init
4)touch lab1.txt
5) echo "This is my first Git file" > lab1.txt
6)git add lab1.txt
7)git commit -m "Add hello.txt"
8)git log
 #2
 Complete Command Sequence
1)git branch
2)git branch feature-branch
3)git switch feature-branch
4)echo "Feature branch changes" > feature.txt
5)git add feature.txt
6)git commit -m "Add feature branch file"
7)git switch master
8)git merge feature-branch
9)git log              OR           git log --oneline –all

#3
mkdir exp3
cd exp3

git init

echo "# Experiment 3" > exp3.txt

git add exp3.txt
git commit -m "Initial commit"

git branch feature
git branch

echo "Changes made in master" >> exp3.txt

git stash
git stash list

git checkout feature

echo "Feature branch work" > feature.txt

git checkout master

git stash apply

git status

git stash drop


#4
mkdir exp4
cd exp4

git clone https://github.com/username/repository.git

ls

cd repository

git status

git remote -v

git log –oneline

#5
$ mkdir exp5
$cd exp5
$git init
$git clone https://github.com/bindiyaaj-blr/GitLab-1BCS307A-
$ls
$git checkout -b feature-branch
$echo "Local feature work" > feature.txt
$git add feature.txt
$git commit -m "Added local feature work"

# Create remote.txt on GitHub main branch

git fetch origin                           Git remote add origin url of reposirory,git remote -v,git fetch origin,git branch -a
git rebase origin/main
git log --oneline --graph --all
git push -u origin feature-branch
ls

#6

cd ~/santhi
mkdir exp6
cd exp6

git init

echo "This is the master branch file" > master.txt
git add master.txt
git commit -m "Initial commit"

git branch feature-branch
git checkout feature-branch

echo "Feature branch implementation" > feature.txt
git add feature.txt
git commit -m "Added feature implementation"

git checkout master

git merge --no-ff feature-branch -m "Merged feature-branch into master"

ls
git log --oneline --graph --all

