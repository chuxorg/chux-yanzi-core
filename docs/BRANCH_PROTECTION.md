# Branch Protection Recommendations

This document describes recommended GitHub branch protection settings for this repository. These settings help ensure changes are reviewed and validated before they are merged.

## Recommended Settings

* Require a pull request before merging
* Require at least one approval
* Require status checks to pass before merging
* Dismiss stale approvals when new commits are pushed
* Prevent force pushes
* Prevent branch deletion
* Optionally require review from code owners

## How to Enable in GitHub

1. Open the repository on GitHub.
2. Go to `Settings` and select `Branches` in the sidebar.
3. Under `Branch protection rules`, select `Add rule`.
4. Enter the branch name pattern (for example, `master`).
5. Enable `Require a pull request before merging`.
6. Enable `Require approvals` and set the number of required approvals to 1.
7. Enable `Require status checks to pass before merging` and select the required checks.
8. Enable `Dismiss stale pull request approvals when new commits are pushed`.
9. Enable `Block force pushes` and `Block deletions`.
10. Optionally enable `Require review from Code Owners`.
11. Click `Create` or `Save changes`.
