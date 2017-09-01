CREATING NEW REPO AND SYNCING WITH GITHUB
-----------------------------------------
git init
touch 'new_file.md'
git add .
git commit -m'Add initial commit'
hub create
OR gem install hub
hub browse
git checkout -b 'new_branch'
add things to file
git add .
git commit -m'added things to file'
git checkout master
git merge new_branch
