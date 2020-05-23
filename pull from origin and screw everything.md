# pull from origin and remove everything locally

Don't like what you've written to your local repo? This is equivalent to deleting your local repo and repulling.

```
git fetch --all
git reset --hard origin/develop
```
