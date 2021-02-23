# PULL REQUESTS

### LINKED ISSUES

A pull request can be linked to an issues and set to auto-close the linked issue when a pull request is merged.

### DRAFT PULL REQUESTS

If a pull request is not ready to be merged or if you are just seeking feedback from collaborators, set pull request status to Draft.

A Draft request cannot be merged until the _Draft_ status is removed. Review requests will nto be automatically sent for Draft pull requests.

### REVIEWS

++Conduct a Review++

Request that one or more contributers review your code prior to a pull request being merged. In fact anyone with _read_ permissions can review your changes 

++Submit a review++

submit a comment & status. 

Status options:
* Comment
* Approve
* Request changes

If the repository owner or a contributor with admin or write permissions selects _Request changes_, then the pull request is blocked until that person approves the changes.

A respoitory owner or admin can overrule _request changes_ (rejected) pull requests and go ahead and force a merge. Useful if a reviewer is unavailable or the owner/admin disagrees with the reviewers objection.

++Enforcing Reviews++

Reviews can be enforced for a branch or set of branches matching a _fnmatch_ syntax pattern. We can enforce 1+ approved reviews to allow a branch to be merged. Approvers can be allocated per pull request and/or a CODEOWNERS file can specifiy code owners for all or part of a repository who will be automatically contacted for a review on a pull request being raised. 
