# Rename Local Branch

If you want to rename a branch while pointed to any branch, do:

```
git branch -m <oldname> <newname>
```

If you want to rename the current branch, you can do:

```
git branch -m <newname>
```

A way to remember this is -m is for "move" (or `mv`), which is how you rename files. Adding an alias could also help. To do so, run the following:

```
git config --global alias.rename 'branch -m'
```

If you are on Windows or another case-insensitive filesystem, and there are only capitalization changes in the name, you need to use -M, otherwise, git will throw branch already exists error:

```
git branch -M <newname>
```

## Credit

[https://stackoverflow.com/questions/6591213/how-do-i-rename-a-local-git-branch](https://stackoverflow.com/questions/6591213/how-do-i-rename-a-local-git-branch)