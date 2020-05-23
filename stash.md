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

```
git stash show -p
```

## List all stashes

You can stash more than once. And your stash is universal across branches within the repo.

```
git stash list
```


## Note: stash doesn't work on merge conflicts

Files that are that contain merge conflict cannot be stashed.
