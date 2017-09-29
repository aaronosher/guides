---
title: Git Checkout
---
## Git Checkout

Checkout is a part of Git's branching functionality. It lets you switch branches and restore old files.

**Table of Contents**
- [Checkout a branch](#checkout-a-branch)
- [Create and checkout a branch simultaneously](#create-and-checkout-a-branch-simultaneously)
- [Setting the origin of a branch](#setting-the-origin-of-a-branch)
- [Forcing a checkout](#forcing-a-checkout)

## Checkout a branch
To see what branches are available, run the command:
```shell
git branch
```

The response will look something like this:
```shell
* master
  branch_1
  branch_2
```

Note the asterisk next to master; this means that you are currently on the master branch and cannot check it out.

To checkout an existing branch, run the command:
```shell
git checkout branch_1
```
In the example `branch_1` is the name of the branch being checked out.
