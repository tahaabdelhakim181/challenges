# C05 — Clean Commit Messages

A good commit message explains WHY the change was made, not just what.

## Bad example
  git commit -m "fix"

## Good example
  git commit -m "fix(auth): handle null token on session expiry"

## Rules I follow
- Use imperative mood: "add", "fix", "update"
- Keep subject line under 72 characters
- Reference the challenge or feature in the prefix
