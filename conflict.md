# Conflict

The easiest way to resolve a merge conflict for a given file is simply to choose `ours` or `theirs`.

```
git checkout --ours index.html
git checkout --theirs _layouts/default.html
```

git will reply with:

> `Updated 1 path from the index`

You'll have to `git add` that file, even though there is no change. It doesn't make sense, but I guess they want you to be absolutely sure this is the file you want to keep. Since you added it, you have to commit and write a message documenting the resolution to your conflict.

