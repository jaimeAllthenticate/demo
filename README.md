# Git commit signing with Allthenticate
Demo repository

```
git config --global gpg.format ssh
git config --global commit.gpgsign true
GPG_KEY=$(ssh-add -L)
git config --global user.signingkey ("$GPG_KEY")
```
then restart terminal

Last edited: 06-11-25
There is a better way to log in
There is a better way to log in
