# Pull Request

In order to review PR locally, this helps to pull PR as branches

Edit `.git/config` the remote origin, add the following

```
fetch = +refs/pull/*/head:refs/remotes/origin/pr/*
```
