# Stash

```
git stash
```

Will put changes made since the last commit into the stash.

## Show what's in the stash

```
sit stash show
```

## Retrieve files from stash

Files in the stash can be popped into the same branch or a different branch.

```
git stash pop
```



## Show diff between stash and head

Show the details, show the patch

```
git stash show -p
```

## List all stashes

You can stash more than once. And your stash is universal across branches within the repo.

```
git stash list
```


## Name your stash

Stashes are named after your last commit message. Not very helpful since your stash often has nothing to do with the commit (otherwise, you would have committed it!).

It's nice to be able name your stashes so you know what is actually in them.

Why would you do this? Super helpful for saving debugging tools that don't need to be in your repo.

```
git stash push -m "AWS debug"
```


## Note: stash doesn't work on merge conflicts

Files that contain a merge conflict cannot be stashed.
