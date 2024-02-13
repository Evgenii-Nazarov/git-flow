# Git course

### Benefits of Version Control / Source control apps

1. A complete change history of every file
2. Branching and merging
3. Traceabilty


## Create an account on Github

1. Go to https://github.com/ follow registration steps and create an account
2. Go to `Your repositories' and create a new one
3. Notice a command `git remote add origin https://github.com/Evgenii-Nazarov/git-flow.git`

## Install git

1. Follow to https://git-scm.com/downloads, follow steps and install git 
2. Run `git` command in terminal to cinfirm installation
3. Set config variables (your email, your user name)
```
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```

## First push

1. Initialize new git repo with `git init`
2. Add changes to `Staging area`: `git add -A`
3. Commit staged changes `git commit -m`
4. Run `git remote add origin https://github.com/Evgenii-Nazarov/git-flow.git`
5. Push your first commit