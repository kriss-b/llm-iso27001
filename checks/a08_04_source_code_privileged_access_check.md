> Install: `brew install gh` (GitHub) or `brew install glab` (GitLab)

Detect the remote platform from `git remote get-url origin`; run `gh api repos/{owner}/{repo}/collaborators --jq '.[] | select(.role_name == "admin") | .login'` for GitHub or `glab api projects/:id/members/all --jq '.[] | select(.access_level >= 40) | {username, access_level}'` for GitLab; verify the list of privileged users is expected and justified.
