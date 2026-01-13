nhojpjop

# Program 1: Setting Up and Basic Commands
git --version
git init
git status
git add <file-name>
git commit -m "commit message"
git log


# Program 2: Creating and Managing Branches
git branch feature-branch
git checkout master
git merge feature-branch


# Program 3: Stashing Changes
git branch
git checkout <branch-name>
git stash save
git stash pop


# Program 4: Collaboration and Remote Repositories
git clone <repository-url>
git pull
git push


# Program 5: Fetch and Rebase
git clone <repository-url>
git pull
git rebase


# Program 6: Merge with Custom Commit Message
git checkout master
git merge feature-branch -m "custom merge message"


# Program 7: Git Tags and Releases
git tag v1.0


# Program 8: Advanced Git Operations (Cherry-pick)
git cherry-pick <commit-id>


# Program 9: View Commit Details
git log
git show <commit-id>


# Program 10: Commits by Author and Date
git log --author="JohnDoe" --since="2023-01-01" --until="2023-12-31"


# Program 11: Display Last Five Commits
git log -n 5


# Program 12: Undo a Commit
git revert abc123
