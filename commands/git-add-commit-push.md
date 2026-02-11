---
description: Git add, commit and push
---

You are on a git repository.

Please do the following:
1. Show git status.
2. Stage all changed files. `git add .`
3. Create a commit. `git commit -m "<commit msg>"`
   - Follow [Conventional Commits](https://www.conventionalcommits.org/).
   - Commit message format:
     <type>(<scope>): <short summary>

   Examples:
   - feat(auth): add login API
   - fix(api): handle null user response
   - chore(ci): update GitHub Actions

4. Push the current branch to origin. `git push origin <current branch>`
