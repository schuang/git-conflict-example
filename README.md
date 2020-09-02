# git-conflict-example

```
$ git checkout branch1  # to see branch1
$ git checkout master
$ git merge branch1     # to merge branch1 into master
```

There will be a merge conflict at this point. Resolve the conflict using 
either manual editing or `git mergetool` (requires some configuration).

To abort the merge:
```
$ git merge --abort
```
