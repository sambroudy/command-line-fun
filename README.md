# Setup

* Fork this Repository [![GitHub forks](https://img.shields.io/github/forks/dbroudy/command-line-fun.svg?style=social&label=Fork&maxAge=2592000)](https://github.com/dbroudy/command-line-fun/fork)
* Do an assignment
* Submit a Pull Request for grading
* Occasionally, [Sync your Fork](#Sync your Fork)

# Assignments

1. [Understanding Pull Requests](understanding-pr)
1. Count the Ss
1. Exponential Backoff

## Sync your Fork
Occasionally, you'll want to get the latest assignments and corrections from this repository your forked copy. This is call syncing a fork or merging with the upstream.

```
git remote add upstream git@github.com:dbroudy/command-line-fun.git
git checkout master
git fetch upstream
git merge upstream/master
```

You only need to add the `upstream` remote the first time.

The GitHub docs have more details about [Syncing a Fork](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/syncing-a-fork)