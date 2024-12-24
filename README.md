# dev-note

# GIT

git config --global user.name "Full Name"
git config --global user.email "email@address.com"

git remote set-url origin "URL"

## First commit
git init
git add .
git commit -am "First commit"
git remote add origin git@github.com:your_github_user/myapplication.git
# Get the README and .gitignore files
git pull origin master
# Send the entire application to Github
git push origin master
