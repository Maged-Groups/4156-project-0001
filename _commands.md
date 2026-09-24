# GIT Commands

## First time on my computer

## identify yourself to OS

```bash
git config --global user.name "MY NAME"
git config --global user.email "MY EMAIL"
```

## OR identify yourself per project

```bash
git config user.name "MY NAME"
git config user.email "MY EMAIL"
```

## Initialize a new repo

```bash
git init
```

## Add file to staging

```bash
git add FILENAME
```

## Add all files to staging

```bash
git add .
git add *
```

## Commit staged changes

```bash
git commit -m "My Message"
```

## Link online repo (GITHUB) to my local repo

```bash
git remote add origin REPO_URL
```

## Push local commits to GitHub

```bash
# First time only
git push -u origin main
# All times
git push
```
