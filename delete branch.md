# Delete branch

## Delete Local Branch

```
git branch -d branch_name
git branch -D branch_name
```

The -d option stands for --delete, which would delete the local branch, only if you have already pushed and merged it with your remote branches.

The -D option stands for --delete --force, which deletes the branch regardless of its push and merge status, so be careful using this one!


## Delete Remote Branch

To delete a remote branch you can use the following command:

```
git push <remote_name> --delete <branch_name>
```

Alternatively, there is this other following option too, which might be just a bit hard to remember:

```
$ git push <remote_name> :<branch_name>
```


## Credit

https://koukia.ca/delete-a-local-and-a-remote-git-branch-61df0b10d323

