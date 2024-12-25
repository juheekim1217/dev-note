# dev-note

# GIT
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
