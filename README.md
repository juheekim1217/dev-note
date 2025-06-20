# dev-note

# GIT
## Init:
…or create a new repository on the command line
echo "# hts" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/juheekim1217/hts.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/juheekim1217/hts.git
git branch -M main
git push -u origin main

## Set your global username/email configuration:
```GIT
git config --global user.name "Full Name"
git config --global user.email "email@address.com"
```

## Initial commit
```GIT
git init
git add .
git commit -m "Initial commit"
git remote add origin git@github.com:your_github_user/myapplication.git
git push -u <remote_name> <local_branch_name>
```

## Create a new branch
```GIT
git checkout -b ＜new-branch＞
```

## Switch to an existing branch
```GIT
git checkout ＜branchname＞
```

# Flutter
## Clear Build Cache
If the icon does not update after regeneration, clear the build cache:

Run the following commands:
```
flutter clean
flutter pub get
```

Rebuild the app:
```
flutter run
```
