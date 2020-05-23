# Remove untracked files

If you want to see which files will be deleted you can use the -n option before you run the actual command:

## Inspect only

```
git clean -n
```

Then when you are comfortable (because it will delete the files for real!) use the -f option:

## Force clean

```
git clean -f
```


## Remove directories

```
git clean -fd
```

## Remove ignored files

```
git clean -fX
```

## Remove ignored and non-ignored files
 
```
git clean -fx
```

**Note the case difference on the X for the two latter commands.**

## Credit

https://koukia.ca/how-to-remove-local-untracked-files-from-the-current-git-branch-571c6ce9b6b1

