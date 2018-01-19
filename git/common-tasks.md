Reset local `master` branch to exactly match the remote branch
----

*This change is destructive*
``` sh
git fetch origin
git reset --hard origin/master

# you can also clean/remove local files if there are untracked files/directories
git clean -fdx
```

---
