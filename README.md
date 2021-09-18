# Sample for dealing with a conflict during rebasing

## Summary

A sample repository for dealing with a conflict during `git rebase`

## Objectives

We have to branches, `main` and `branch`. We want to take the changes that were introduced by `branch`and apply them on `main` by `git rebase`.

Three commits exist from the common ancestor of the two branches. Therefore, `git rebase main` from `branch` will apply three patches, and consequently, three commits. However, during the rebasing, the procedure is stopped because of some conflicts.

You have to resolve the conflict and complete the rebasing proceduer.

## How to use

```sh
git switch -c branch origin/branch
git rebase main
```

## LICENCE

CC0
