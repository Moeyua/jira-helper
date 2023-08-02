# prometheus

Add this prometheus repository as a remote.

```
git remote add prometheus https://github.com/Moeyua/prometheus.git
```

Then run git fetch to update the changes

```
git fetch --all
```

Then is possible to merge another branch from the new remote to your current one.

```
git merge prometheus/main --allow-unrelated-histories
```
