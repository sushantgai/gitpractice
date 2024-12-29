# Git Practice

This document is for practicing Git commands.

## Common Git Commands

- `git init`: Initialize a new Git repository.
- `git clone <repository>`: Clone an existing repository.
- `git status`: Show the working directory status.
- `git add <file>`: Add a file to the staging area.
- `git commit -m "message"`: Commit changes with a message.
- `git push`: Push changes to the remote repository.
- `git pull`: Fetch and merge changes from the remote repository.
- `git branch`: List, create, or delete branches.
- `git checkout <branch>`: Switch to a different branch.
- `git merge <branch>`: Merge a branch into the current branch.

## Practice Steps

1. Initialize a new repository:
    ```sh
    git init
    ```

2. Create a new file and add it to the repository:
    ```sh
    echo "# My Project" > README.md
    git add README.md
    git commit -m "Initial commit"
    ```

3. Create a new branch and switch to it:
    ```sh
    git branch new-feature
    git checkout new-feature
    ```

4. Make changes and commit them:
    ```sh
    echo "Some changes" >> README.md
    git add README.md
    git commit -m "Add some changes"
    ```

5. Merge the new branch into the main branch:
    ```sh
    git checkout main
    git merge new-feature
    ```

6. Push the changes to the remote repository:
    ```sh
    git push origin main
    ```

Happy coding! 