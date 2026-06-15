# Cherry-pick Demo

## Scenario
A bug was fixed on the hotfix/bugfix branch.
The fix needed to be applied to main without merging the whole branch.

## Solution
  git cherry-pick <commit-hash>

This copies the specific commit onto the current branch cleanly.
