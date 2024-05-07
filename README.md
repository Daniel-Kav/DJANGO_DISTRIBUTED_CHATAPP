# Gitignore Cheatsheet

The `.gitignore` file is used to specify intentionally untracked files to ignore. It uses glob patterns to match files and directories.

### Rules for Matching Patterns in .gitignore Files

- **Wildcard**: Use asterisk (\*) to match zero or more characters.

  - Example: `*.log` matches all files with the ".log" extension.

- **Directory Wildcard**: Use a trailing slash (/) to match directories.

  - Example: `logs/` matches the "logs" directory.

- **Negation**: Prefix a pattern with an exclamation mark (!) to negate it.

  - Example: `!important.log` excludes the "important.log" file from being ignored.

- **Comments**: Lines starting with a hash (#) are comments and are ignored.
  - Example: `# Ignore temporary files`

For more information on .gitignore patterns, refer to the [official documentation](https://git-scm.com/docs/gitignore).
