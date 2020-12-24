# Git notes

![git-stages-image](https://raw.githubusercontent.com/solisjoaquin/git-github-notes/main/git.png)

## Common terminal comands

```
pwd 
ls 
-al
```
## Set git config
```
git config --list
```
## Set username and email

username
```
git config --global user.name "Username"
```
email
```
git config --global user.email "user@email.com"
```

## Init a git project

```
git init
```
## See untracked files

```
git status
```

## Commit changes
```
git commit -m "Message"
```

## See all commits of a file 

```
git log filename.txt
```

## See the changes of a file
```
git show filename.txt
```

## Compare 2 commits

```
git diff #paste_commit_code_1 ##paste_comit_code_2
```

## Commit without a message using Vim
If we only use git commit without a message, a new editor will be open. This code editor is called Vim
* write the commit message 
* ESC + Shift + ZZ to scape

## Return to a specific commit
* hard: delete the commit until the specific commit
```
git reset #paste_commit_code --hard
```
## Return to an specific commit but with the chance to return to the lastest
return to a specific commit
```
git checkout #commit_code filename.txt
```
return again to the lastest version
```
git checkout master filename.txt
```

## See the content of a file
```
cat filename.txt
```

