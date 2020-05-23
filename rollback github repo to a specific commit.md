# Rollback github repo to a specific commit

WARNING: you're rewriting history. Using this is dangerous in a collaborative environment. Make sure your team pulls after this change, so they don't push the very commit(s) you tried to get rid of.

```
git reset --hard <old-commit-id>
git push -f <remote-name> <branch-name>
```


## Credit

[https://stackoverflow.com/questions/4372435/how-can-i-rollback-a-github-repository-to-a-specific-commit](https://stackoverflow.com/questions/4372435/how-can-i-rollback-a-github-repository-to-a-specific-commit)