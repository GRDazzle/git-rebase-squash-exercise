

## Git rebase and commit squashing exercise

### Objective

In this exercise we will practice how to squash incomplete commits into two commits.


### Exercise

Start the exercise by forking and cloning the repository.

The `practice_branch` branch represents a feature branch that is to be rebased (moved) and squashed.

On the `practice_branch` branch you find a script that prints a haiku:

The haiku is great but the
commit history on
the `haiku` branch is not (on purpose):

```shell
$ git log --oneline

c1ed0be Fix erro in initial hiku file
c7945ec Move some blocks to hiku impl file
261900f add impl file
b5daf2e Add missing message
5a43d92 Add hiku file
c50a463 initial commit
```

Your task is to 

- Rebase the branch on top of master branch
- Squash (first commit)
    - Add hiku file
    - Add missing message 
    - Fix erro in initial hiku file
- Squash (second commit)
    - add impl file
    - Move some blocks to hiku impl file
