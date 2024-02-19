# Class 3: Building Files in VCS

| Term              | Definition                                                                                                                               |
| ----------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| Working Directory | The directory on your local machine where you modify, edit, and create files. It represents the current state of your project.           |
| Staging           | The intermediate area where you gather and organize changes before committing them to the version control system.                        |
| Committing        | The process of saving changes from the staging area to the version control system, creating a new snapshot of your project's state.      |
| Branching         | A parallel version of your project, allowing you to work on features or changes without affecting the main project until ready to merge. |

## Creating a Local Repository

- **Using command line**

```bash
git init
```

This sets up a new Git repository in your current directory.

- **Using Visual Studio Code**

- Create a folder name `vscode-new`
- Open it suing vscode
- Create a file like `Readme.md`
- Public to Github
  - Press `Ctrl + Shift + P` (on Windows), or `Command + Shift + P` (on Mac)
  - Select whether to Publish a **private** or a **public** repository
  - Select file to include

## Creating Required Directories

## Branching

1. **Create a New Branch:**

   - Command: `git branch branch_name`
   - Example:

   - ```bash
     git branch feature-branch
     ```

2. **Switch to a Branch:**

   - Command: `git checkout branch_name` or `git switch branch_name` (Git version 2.23 and later)
   - Example:

   - ```bash
     git checkout feature-branch
     ```

3. **Create and Switch to a New Branch:**

   - Command: `git checkout -b new_branch_name` or `git switch -c new_branch_name` (Git version 2.23 and later)
   - Example:

   - ```bash
     git checkout -b new-feature
     ```

4. **Push a Branch to a Remote Repository:**

   - Command: `git push remote_alias branch_name`
   - Example:

   - ```bash
     git push origin feature-branch
     ```

5. **Set Upstream Branch (Tracking Relationship):**

   - Command: `git push --set-upstream remote_alias branch_name` or `git branch --set-upstream-to=remote_alias/branch_name`
   - Example:

   - ```bash
     git push --set-upstream origin feature-branch
     ```

6. **Push to Default Upstream Branch:**

   - Command: `git push`
   - Example: After setting upstream, ```bash
     git push
     ```will automatically push changes to the default upstream branch.

     ```

7. **Clone a Specific Branch:**

   - Command: `git clone -b branch_name repository_url`
   - Example:

   - ```bash
     git clone -b main https://github.com/example/repo.git
     ```

8. **Fetch Changes from Upstream:**

   - Command: `git fetch upstream branch_name`
   - Example:

   - ```bash
     git fetch upstream feature-branch
     ```

9. **Compare Local and Remote Branch:**

   - Command: `git log origin/branch_name..branch_name`

10. **Display Content of a File in a Specific Commit:**

    - Command: `git show commit_hash:path/to/file`

11. **Display Content of a File in the Current Commit:**

    - Command: `git show HEAD:path/to/file`

12. **Set Default Remote Alias for Push:**

    - Command: `git push -u remote_alias branch_name`
    - Example:

    - ```bash
      git push -u myfork feature-branch
      ```

13. **Display Current Branch:**
    - Command: `git branch --show-current`
