# Undo Cheatsheet

## Discard changes in working directory
  git restore <file>
  → brings the file back to the last committed state

## Unstage a file
  git restore --staged <file>
  → removes file from staging area, keeps changes in working directory

## Undo last commit (keep changes)
  git reset --soft HEAD~1
  → moves HEAD back one commit, staged changes remain

## Undo last commit (discard changes)
  git reset --hard HEAD~1
  → moves HEAD back one commit, all changes lost — use with caution
