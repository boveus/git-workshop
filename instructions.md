CREATING NEW REPO AND SYNCING WITH GITHUB
-----------------------------------------
git init
touch 'new_file.md'
git add .
git commit -m'initial'
hub create
OR gem install hub
hub browse
git checkout -b 'new_branch'
add things to file
git add .
git commit -m'added things to file'
git checkout master
git merge new_branch

PULL REQUESTS
-------------
git checkout -b 'pull_request'
git push origin pull_request
hub browse
compare & pull request
base/compare
reviewers/assignees
create pull request
merge pull request
delete branch
