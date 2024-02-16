# GitCollab

# Git Collaboration Project

## Git Workflow Practice Scenarios

### Scenario 1: Basic Git Workflow with Text Files

Objective: Learn to commit changes and push to a remote repository.

Setup
Create a Git repository containing a README.md and a simple text file (notes.txt).
Task
Update notes.txt with new content.
Commit your changes.
Push them to the remote repository.

### Scenario 2: Branching and Merging

Objective: Practice creating branches, making commits in branches, and merging them back to the main branch.

Setup
Start with a basic web project with index.html, style.css, and script.js.
Task
Create a new branch called feature-add-login.
Add a basic login form to index.html and corresponding styles in style.css.
Commit your changes to this branch.
Merge them into the main branch.

### Scenario 3: Handling Merge Conflicts

Objective: Learn to resolve merge conflicts that occur when two branches have edited the same lines in a file.

Setup
Ensure the main branch has an updated version of index.html with some content.
Task
Create two branches, update-header and update-footer.
In each branch, make changes to the same parts of index.html.
Try merging both branches into the main branch one after the other and resolve the resulting merge conflict.

### Scenario 4: Collaboration and Pull Requests

Objective: Practice collaborating through forks and pull requests.

Setup
One person should host the main repository. The other should fork it and clone their fork.
Task
The collaborator adds a new feature or fixes an issue in their fork, commits the changes, and pushes them to their fork.
Create a pull request to the main repository.
Review and merge the pull request.

### Scenario 5: Reverting Changes

Objective: Learn to revert changes using Git.

Setup
Ensure the repository has several commits.
Task
Introduce a deliberate "bug" or mistake in one of the files and commit it.
Use git revert to undo this commit.
Explore the history with git log to understand what happened.

### Scenario 6: Using Git Stash

Objective: Practice using git stash to save uncommitted changes temporarily.

Setup
Begin with ongoing changes that are not yet ready to be committed.
Task
Use git stash to temporarily shelve your changes.
Switch to a different branch to work on another task.
Come back to your original branch and apply your stashed changes with git stash pop.

### Scenario 7: Interactive Rebase

Objective: Learn to use interactive rebase for cleaning up commit history.

Setup
Create a new branch and make several small commits that could logically be combined into a single commit.
Task
Use git rebase -i HEAD~<number_of_commits> to squash commits into a single commit, reword commit messages, or fix up commits.
