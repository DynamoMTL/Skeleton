# Skeleton: A Beautiful Boilerplate for Responsive, Mobile-Friendly Development

This is Dynamo's fork of the official Skeleton repository. This enables us to
keep sixteen- and twelve-column versions of the grid system up-to-date with the
upstream project. The master branch will reflect the upstream repository, while
the `twelve-column-grid` branch will reflect a twelve-column version of the
Skeleton grid.

For general information about Skeleton, please visit:
http://www.getskeleton.com/

## Upstream changes

To merge in upstream changes:

    git clone git@github.com:DynamoMTL/Skeleton.git
    cd Skeleton/
    git remote add upstream https://github.com/dhgamache/Skeleton.git
    git fetch upstream
    git merge upstream/master

Be sure to inspect the merged-in upstream changes and assess whether they need
to be ported into the twelve-column branch.
