# Gitignore Cheatsheet

The `.gitignore` file is used to specify intentionally untracked files to ignore. It uses glob patterns to match files and directories.

### Rules for Matching Patterns in .gitignore Files

| Pattern          | Explanation                                                  | Example                    |
| ---------------- | ------------------------------------------------------------ | -------------------------- |
| `*.log`          | Matches all files with the ".log" extension.                 | `*.log`                    |
| `logs/`          | Matches the "logs" directory.                                | `logs/`                    |
| `!important.log` | Excludes the "important.log" file from being ignored.        | `!important.log`           |
| `# Comment`      | Lines starting with a hash (#) are comments and are ignored. | `# Ignore temporary files` |

For more information on .gitignore patterns, refer to the [official documentation](https://git-scm.com/docs/gitignore).
