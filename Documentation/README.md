# Additional documentation and notes

## Sync the bootstrap_package fork with the upstream repository

Before you can sync, you must configure a remote that points to the upstream repository in Git:

    git remote add upstream https://github.com/benjaminkott/bootstrap_package.git

Fetch the changes from upstream repository

    git fetch upstream

Better merge in development branch

    git checkout development
    git merge upstream/master
