# Version control systems in development environments

## Git Cheatsheet

- Set a Username

```bash
git config --gLobal user.name "<firstname Lastname>"
```

- Set an Email address

```bash
git config --gLobal user.email "<valid-email>"
```

- Initialize an existing directory as a Git repository

```bash
git init
```

- Link the local repository to an empty GitHub repository

```bash
git remote add origin <repo_url>
```

- Clone (download) a repository that already exists on GitHub.

```bash
git clone <repo_url>
```

- Show modified files in working directory, staged for your next commit

```bash
git status
```

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

- Display the content of your global Git configuration

```bash
git config --global --list
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