---
layout: post
title: Rewriting Git Commit History
---

This bad habits of not writing sane commit message is really hard to get away.

<<<<<<< HEAD
```bash
=======
```
>>>>>>> bc8315e2c93ac66ef79684d5c5ee6c7176aee414
git checkout --orphan tempBranch
git add -A  # Add all files and commit them
git commit
git branch -D master  # Deletes the master branch
git branch -m master  # Rename the current branch to master
git push --set-upstream origin master # Set current branch to origin:master
git push --set-upstream origin master --force
```

<<<<<<< HEAD
use `git push origin --delete devel` to delete __origin:devel__ branch
=======
use `git push origin --delete devel` to delete origin:devel branch
>>>>>>> bc8315e2c93ac66ef79684d5c5ee6c7176aee414
