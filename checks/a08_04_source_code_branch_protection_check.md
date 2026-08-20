> Install: `brew install gh` (GitHub) or `brew install glab` (GitLab)

Detect the remote platform from `git remote get-url origin`; run `gh api repos/{owner}/{repo}/branches/main/protection` for GitHub or `glab api projects/:id/protected_branches` for GitLab; check passes if branch protection is configured on the main branch.
