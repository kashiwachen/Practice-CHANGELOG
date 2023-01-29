# Practice of `git-chglog`

This is a repo for self-learning, and searching for appropriate workflow

## Workflow Idea

1. Create and develope a feature branch. We may have lots of commits under this branch.
1. Merge the feature branch with `squash merge` in PR, and have the commit with the format that `git-chglog` will recognize.
1. Create and switch to antoher branch(`release-x`) for updating the CHANGELOG
1. Attach tags on the commits.
1. Use `git-chglog -o CHANGELOG.md` to generate logs.
1. Make the PR to merge the CHANGELOG message.
1. DONE.
