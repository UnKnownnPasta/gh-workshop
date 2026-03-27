# Github Workshop project

## Step 1 - Install git
go to https://git-scm.org and download git
set default editor as vim

## Step 2 - configure git
user:
```bash
git config --global user.email "<youremail>"
git config --global user.name "<yourname>"
```

## Step 3 - create project and files
```bash
mkdir project 
cd project
cat >> file1.txt << EOF
> this is some text
> EOF
```

## Step 4 - make git repo local
```bash
git init 
git add .
git commit -m "message"
git remote add origin <url> 
git branch -M main
git push -u origin main
```
