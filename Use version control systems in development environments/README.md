# Version control systems in development environments

## Git Cheatsheet

### Setup Credentials

- Set a Username

```bash
git config --gLobal user.name "<firstname Lastname>"
```

- Set an Email address

```bash
git config --gLobal user.email "<valid-email>"
```

- Display the content of your global Git configuration

```bash
git config --global --list
```

### Initialization and linking with remote

- Initialize an existing directory as a Git repository

```bash
git init
```

- Link the local repository to an empty GitHub repository

```bash
git remote add origin <repo_url>
```

- Get link to remote

```bash
git remote get-url origin
```

### Cloning

- Clone (download) a repository that already exists on GitHub.

```bash
git clone <repo_url>
```

- Clone with limited history

```bash
git clone --depth=1 <repo_url>
```

### Managing Giles

- Show modified files in working directory, staged for your next commit

```bash
git status
```

- Display the commit history in a Git repository

```bash
git log
```

- Show what revision and author last modified each line of a file

```bash
git blame <file_name_with_path>
# without Username
git blame -s <file_name_with_path>
```

### Stage & Snapshot

- Add a file as it looks now to your next commit (stage)

```bash
git add <file_name>
```

- Add all changed files to staging area

```bash
git add .
```

- Commit your staged content as a new commit snapshot

```bash
git commit -m "<descriptive message>"
```

- Amending commit

```bash
git commit --amend -m "<new message>"
# keep old message
git commit --amend --no-edit
```

### Branching

- To check which branch that is

```bash
git branch
```

- Create new branch

```bash
git branch <branch-name>
```

- Creates a new branch & switch to that branch using one command only

```bash
git checkout -b <branch-name>
```

- Deletes the specified branch

```bash
git branch -d <branch-name>
```

### Update Local & Remote repos

- Updates local working branch with all new commits from the corresponding remote branch on `GitHub.com`
- `git pull` is a combination of `git fetch` and `git merge`

```bash
git pull origin <branch_name>
```

- Uploads all local branch commits to GitHub

```bash
git push origin <branch_name>
```

- Synchronize your local repository with the remote repository on `GitHub.com`

```bash
git fetch
```

### Merging

- Merge <branch> into the current branch

```bash
git merge <branch_name>
```

## See 👀 Github like vscode

- Add **1s** after the word github in the address of that Repo
  - `https://github1s.com`
- Add **box** after the word github in the Repo address
  - `https://githubbox.com`
- Changing the **.com** to **.dev** Repo address
  - `https://github.dev`

## `.gitignore`

- The `.gitignore` file instructs Git on which files or directories to exclude from version control
- It helps maintain a cleaner repository by excluding files like compiled binaries, temporary files, and configuration files specific to individual environments, preventing them from being unintentionally committed
- Improving collaboration efficiency.

## Double quotation marks around text

In some Git commands, using double quotation marks around text is necessary, especially when the text includes spaces or special characters

## Links

- [ByteByteGo = How Git Works: Explained in 4 Minutes](https://www.youtube.com/watch?v=e9lnsKot_SQ)
- [ByteByteGo = CI/CD In 5 Minutes](https://www.youtube.com/watch?v=42UP1fxi2SY)
- [What is Git? Explained in 2 Minutes!](https://www.youtube.com/watch?v=2ReR1YJrNOM)

## VSCode Extensions

- [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
- [Git Prefix](https://marketplace.visualstudio.com/items?itemName=srmeyers.git-prefix)
- [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)
- [GitHub Pull Requests](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)
- [GitHub Repositories](https://marketplace.visualstudio.com/items?itemName=GitHub.remotehub)
- [GitHub Codespaces](https://marketplace.visualstudio.com/items?itemName=GitHub.codespaces)
