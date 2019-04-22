---
title: My Top 5 Git Shortcuts
description: 
---

###My Top 5 Git shortcuts


####1) add and commit at the same time

Rather than
```
git add .
git commit -m "update"
```

Use:

```
git commit -am "update"
```

I should note here that this only seems to work for files in the current folder. If you have files in sub folders you'll need to move into them or use the longhand version :-(
