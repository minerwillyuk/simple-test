# WORKING WITH BRANCHES
### COMPARING BRANCHES

Range operators (.. and ...) are used when compare branches using diffing.

    >git diff branchA..branchB

Show difference between tips of both branches

    >git diff branchA...branchB

Show difference between last common ancestor of _branchA_ and _branchB_ and tip of brancb

GOTCHA: Note that the range operators act differently when using git log. Don't get caught out!

### BRANCH PROTECTIONS

1. Block delete and force merge actions on a branch
2. Require status checks (CI actions) to pass to allow a merge
3. Require pull request reviews from one or more reviewers
4. Require code owners to review (see CODEOWNERS file)
5. Require a signed commit to ensure commit is signed and verified by a trusted contributer

++QUESTION:++ Do all code owners have to review or just up to the number of required reviews for a pull request? 
### TIPS

Always fetch and merge origin/main with local/main and then rebase on your feature branch immediately before pushing your feature to origin and raising a pull request

Delete a feature branch when merged. Avoid using long running branches for features.

Yadda yadda yadda...
