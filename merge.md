# merge

`git merge main` 

Will merge commits **FROM** main **to** the branch you're currently on.


## Best practice: make a new branch before you merge

```
// from feature branch
git checkout -b attempt-to-merge-develop-with-feature
git merge develop
```

Resolve the conflicts, if any.

Then, add, commit, push.

If stuff gets too scary and you need to retreat, you can delete this attempt-to-merge branch.



## undo? Abort!

```
git merge --abort
```

