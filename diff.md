# git diff

```
git diff
```

Show code changes between changes in red and the last commit.

## NOTE: git diff only works on UNSTAGED changes

In other words, `git diff` won't work after you `git add .`

I assume the reasoning behind this is that you wouldn't add something to staging if you were totally unaware of the changes. If you were a sane person, you would be fully aware of the changes you make to your files before you `git add`.
