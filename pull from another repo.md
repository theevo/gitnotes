# Pull from another repo

This will pull all branches and commits

```
git remote add upstream (url)
git pull upstream
```


```
➜  Alarm git:(StartingOver) git remote add upstream git@github.com:JHaz3/Alarm.git
➜  Alarm git:(StartingOver) git pull upstream
remote: Enumerating objects: 63, done.
remote: Counting objects: 100% (63/63), done.
remote: Compressing objects: 100% (37/37), done.
remote: Total 63 (delta 25), reused 53 (delta 20), pack-reused 0
Unpacking objects: 100% (63/63), done.
From github.com:JHaz3/Alarm
 * [new branch]      Develop                   -> upstream/Develop
 * [new branch]      LevelingUp                -> upstream/LevelingUp
 * [new branch]      WorthlessbranchTimeWaster -> upstream/WorthlessbranchTimeWaster
 * [new branch]      master                    -> upstream/master
 * [new branch]      part1Solution             -> upstream/part1Solution
 * [new branch]      part2Solution             -> upstream/part2Solution
 * [new branch]      projectComplete           -> upstream/projectComplete
 * [new branch]      projectStart              -> upstream/projectStart
 * [new branch]      updates                   -> upstream/updates
You asked to pull from the remote 'upstream', but did not specify
a branch. Because this is not the default configured remote
for your current branch, you must specify a branch on the command line.
```