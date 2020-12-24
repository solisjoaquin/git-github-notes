# Connet Github to Git with SSH

## To see the git configuration
```
git config -l
```
## Set an email
```
git config --global user.email "user@email.com"
```

## Set key 

```
ssh-keygen -t rsa -b 4096 -C "user@email.com" 
```

That will generate a public and a private key

## Check the keys for Windows and Linux

```
eval $(ssh-agent -s)
```
that will return a number with the word "Agent pid"

## Add the key

Site on home directory and connect the private key
```
ssh-add ~/ssh/id_rsa
```

# Go to setting on Github

* Click on SSH and GPG keys and add a new key
* Go to repo and clone it but select the SSH option
* Copy that SSH-url

# Go to local repo and open the terminal 

```
git remote set-url origin (paste-the-github-SSH-text)
```
