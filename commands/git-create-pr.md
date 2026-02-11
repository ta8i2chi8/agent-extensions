---
description: Create PR
---

You are in a git repository.

Please do the following:

1. Detect the current git branch name.

2. Read `.github/PULL_REQUEST_TEMPLATE.md` and use it as the base of the PR body.

3. Create a Pull Request using GitHub CLI.
   - The title should be concise and reflect the code changes.
   - The body should follow the Pull Request template.

Example command:
gh pr create \
  --title "<title>" \
  --body "<body based on PULL_REQUEST_TEMPLATE.md>"
