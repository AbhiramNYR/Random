
ex.1
install git

ex.2
git config --global user.name "Your Name"
git config --global user.email "Your Email"
git config --list --global

ex.3
git clone "Copy link"
git init
git add .
git push orgin main
git commit -m

change default branch
git config --global init.defaultBranch main

create and merge branch
git checkout -b <feature-branch>
git merge <feature-branch>

add remote repository
git remote add orgin <remote-url>

push
git push orgin main

issues
git commit -m "Fix #1:Done"
git add .
git push orgin main

fork
git clone https://github.com/YOUR-USERNAME/Spoon-Knife
git remote -v
git remote add upstream https://github.com/ORIGINAL-OWNER/Spoon-Knife.git
git remote -v

