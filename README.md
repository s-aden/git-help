git-help
========
# remove a directory from the remote branch i.e. if it is pushed to remote and later ignored by .gitignore

git rm -r --cached some-directory
git commit -m 'Remove the now ignored directory "some-directory"'
git push origin master
