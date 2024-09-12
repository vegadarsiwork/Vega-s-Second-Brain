
2024-08-30 09:17

Status:

Tags: [[NIAT]] [[Definitions]]

________________________________________________________________________



# Introduction to Git

Git is a free, open-source distributed version control system that allows multiple people to work on a project simultaneously without interfering with each other's work. It helps developers manage and track changes to the source code over time.

### Key Features of Git:

- **Version Control**: Git tracks changes to files, allowing you to revert to previous versions if needed. Each change is stored as a "commit," which represents a snapshot of the project at a specific point in time.
- **Branching and Merging**: Git allows you to create branches, which are separate copies of the project where you can work on different features or fixes independently. Once the work is complete, you can merge the branches back together.
- **Distributed System**: Unlike centralized version control systems, Git allows every developer to have a full copy of the repository, including its entire history. This makes Git more robust and faster, as you can work offline and still have access to the complete project history.
- **Collaboration**: Git is commonly used in collaboration with platforms like GitHub, GitLab, or Bitbucket, which provide additional features such as code hosting, issue tracking, and pull requests, making it easier for teams to work together.

### Basic Git Workflow:

1. **Clone a repository**: Copy an existing Git repository to your local machine.
2. **Create a branch**: Create a new branch to work on a feature or fix.
3. **Commit changes**: Save snapshots of your changes to the local repository.
4. **Push changes**: Upload your changes to a remote repository.
5. **Merge branches**: Combine your changes with the main branch or other branches.

### Common Git Commands:

- `git init`: Initialize a new Git repository.
- `git clone <repository-url>`: Clone an existing repository.
- `git add <file>`: Stage changes to be committed.
- `git commit -m "commit message"`: Commit staged changes with a message.
- `git push`: Push commits to a remote repository.
- `git pull`: Fetch and merge changes from a remote repository.
- `git branch`: List, create, or delete branches.
- `git checkout <branch-name>`: Switch to a different branch.
- `git merge <branch-name>`: Merge changes from one branch into another.

- **Commit**: A saved snapshot of your project’s state, recording changes and a descriptive message.
- **Snapshot**: A specific state of your project at a given time, captured in a commit.
- **Rollback**: Reverting the project to a previous state by undoing changes or commits.
- **Staging**: Selecting changes to include in the next commit, held in the staging area.
- **Push**: Sending your commits to a remote repository.
- **Pull**: Fetching and merging changes from a remote repository into your local one.
- **Branch**: A separate line of development for features or fixes.
- **Merge**: Combining changes from one branch into another.
- **Revert**: Creating a new commit that undoes a previous commit.
- **Checkout**: Switching between branches or commits.

### Tracking Files:

- **Tracking**: Git monitoring a file for changes.
- **Untracked Files**: Files not yet monitored by Git.
- **Staging Area**: Where tracked changes are organized before committing.
- **Unstaged Changes**: Modifications to tracked files not yet added to the staging area.
- **Add (git add)**: Move changes to the staging area for inclusion in the next commit.
- **Ignore (.gitignore)**: A file that lists files and directories Git should not track.


# References

