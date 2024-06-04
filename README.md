"# git-test2" 

To create a repository from the command line, first create and empty respository on GitHub. Then create an empty directory on your local machine. To turn the empty directory into a repository and push to GitHub use:
```
echo "# git-test2" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/cttedwards/git-test2.git
git push -u origin main
```
following which, any local changes can be pushed using:
```
git add <filename>
git push origin main
```
To pull changes from the GitHub repository onto your local machine use:
```
git remote -v
```
to check the remote, and then:
```
git pull
```

Status of the local repository can be checked any time using:
```
git status
```
