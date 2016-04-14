---
layout: post
title: Rewriting Git Commit History
---

This bad habits of not writing sane commit message is really hard to get away.

```
git checkout --orphan tempBranch
git add -A  # Add all files and commit them
git commit
git branch -D master  # Deletes the master branch
git branch -m master  # Rename the current branch to master
git push --set-upstream origin master # Set current branch to origin:master
git push --set-upstream origin master --force
```

use `git push origin --delete devel` to delete origin:devel branch