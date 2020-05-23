# Rollback github repo to a specific commit

WARNING: you're rewriting history. Using this is dangerous in a collaborative environment. Make sure your team pulls after this change, so they don't push the very commit(s) you tried to get rid of.

```
git reset --hard <old-commit-id>
git push -f <remote-name> <branch-name>
```

## commit-id

You get it from GitHub or `git log`. Copy the full bajillion-character long id or just the first 7 characters. They're equivalent!


## Credit

[https://stackoverflow.com/questions/4372435/how-can-i-rollback-a-github-repository-to-a-specific-commit](https://stackoverflow.com/questions/4372435/how-can-i-rollback-a-github-repository-to-a-specific-commit)