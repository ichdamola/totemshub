1. FORKING A REPOSITORY

Forking a repostory allows you to freely experiment with changes without affecting the original project.
A Fork is a copy of repository.
Mostly forks are used to either propose changes to someone else's project or to use someone else's project as a starting point of your own idea.



2. CLONING A REPOSITORY
Cloning a repository pulls down a full copy of all the repository data that GitHub has at the point in time. It is used to copy an existing Git repository into a new local directory. You can push your changes to the remote repository on GitHub or pull other people's changes fom GitHub.
To clone a repository on GitHub, open Terminal, change the current directory to where you want to store the cloned directory. Type 'git clone' and then paste the URL you copied earlier. Then press 'enter' to create your local name.



3. CREATING A PULL REQUEST
Pull request lets you tell others about changes you've pushed to a branch in a repository on GitHub.
Once a pull request is opened, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch.
To create a Pull Request on GitHub, switch to the branch that you want to create a pull request for. Click 'Create Pull Request'.
On GitHub,confirm that the branch where you want to merge your changes.
Confirm that the branch in the compare:drop-down menu is the topic branch where you made your changes.
Type a title and description for your pull request.



4. ADD, COMMIT, PUSH
ADD tells git that you want to include updates to a particular file in the next commit. It doesn't affect the repository in any significant way.
The git ADD command adds a change in the working directory to the staging area.
COMMITS are the core building block units of a Git project timeline.
The git COMMIT command captures a snapshot of the project's currently staged changes. 
PUSH is how you transfer commits from your local repository to a remote repository.
The git PUSH command is used to upload local repository content to a remote repository.



5. UPDATING A CLONED REPOSITORY
If you have cloned the repository to your local machine, you can add the original GitHub repository as a "remote". Then you can fetch all the branches from that original repository, and rebase your work to continue working on the upstream version.
From command line:
Add the remote, call it 'original'. (git remote add original)
Fetch all the branches of the remote tracking branches such as original. (git fetch original)
Make sure you're on your original branch. (git checkout original)
Rewrite the original branch so that any commits of yours that aren't already in original are replayed on top of the other branch. (git rebase original)
If you don't want to rewrite the history of the original branch, then you should merge it. (git merge original)



6. PULL AND FETCH
The git PULL is a convenient shortcut for completing both git fecth and git merge in the same command.
It is used to fetch and download content from a remote repository and immediately uodate the local repository to match that content.
It first runs git fetch which downloads content from the specified remote repository. Then a git merge is executed to merge the remote content refs and heads into a new local merge commit.
The git FETCH command is used to retrieve new work done by other people .
Fetching from a repository grabs all the new remote tracking branches and tags without merging those changes into your own branches.
It downloads commits, files and refs from a remote repository into your local repository.
Fetching is what you do when you want to see what everybody else has been working on.