# Basic_Git_Commands

* set global username and email

**git config --global user.name "github user name"
**git config --global user.email "github email"

* First initialize a local repository

git init Repo_Name

* Change to that directory

cd Repo_Name

* Create a markdown file in that repo

echo "# Title of Page" >> Filename.md

* Open markdown file and edit accordingly

* Add markdown file

git add Filename.md

* Commit changes

git commit -m "changes"

* Create a remote repository in github to add the file to, or use an existing repo

* Link to the remote repo

git remote add origin https://github.com/tbshirey/BasicGitInfo.git

**or is repo already exists

git fetch https://github.com/tbshirey/BasicGitInfo.git

* Push the file to the remote repo

git push -u origin master

* If push is rejected because the remote contains work that you do not have locally, then you have to integrate the remote changes locally

git pull
ctrl+x



