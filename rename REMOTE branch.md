# Rename Remote Branch

There are a few ways to accomplish that:

1. Change your local branch and then push your changes
2. Push the branch to remote with the new name while keeping the original name locally


## Rename the local branch to the new name
```
git branch -m <old_name> <new_name>
```

## Delete the old branch on remote - where <remote> is, for example, origin
```
git push <remote> --delete <old_name>
```

## Or shorter way to delete remote branch [:]
```
git push <remote> :<old_name>
```

## Push the new branch to remote

```
git push <remote> <new_name>
```

## Reset the upstream branch for the new_name local branch

```
git push <remote> -u <new_name>
```

## Credit

https://stackoverflow.com/questions/30590083/how-do-i-rename-both-a-git-local-and-remote-branch-name