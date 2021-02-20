# BRANCHES
### COMPARING BRANCHES

    >git diff branchA..branchB

Show difference between tips of both branches

    >git diff branchA...branchB

Show difference between last common ancestor of branchA and branchB and tip of brancb
### BRANCH PROTECTIONS

1. Block delete and force merge actions on a branch
2. Require status checks (CI actions) to pass to allow a merge
3. Require pull request reviews from one or more reviewers
4. Require a code owner review
5. Require a signed commit to ensure commit is signed and verified by a trusted contributer