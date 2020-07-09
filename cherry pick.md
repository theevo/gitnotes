# cherry pick

Cherry pick allows you to take a commit from one branch and commit it to another branch.

Assumptions:
1. You have already committed the commit you want to cherry pick. The name of the branch which contains this commit is not necessary for a cherry pick operation.
2. You have the commit hash is, which you probably got from `git log`.
3. You are currently checked in to the branch that will be receiving the cherry-picked commit. Maybe it's `main`

If you plan to submit a Pull Request, you'll need a new branch.

```
git checkout -b <destinationBranch>
```

```
git cherry-pick <commit hash>
```

After executing this last command, destinationBranch will contain the cherry-picked commit.

From here you can Pull Request using that destinationBranch.
