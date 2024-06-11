These are my basic global git configuration files. They include:
* Committer name and email address
* Make git ignore `*~` backup files
* Don't allow committing or pushing to main, master, or a branch not
  starting with my username in any repo.

To install,

```
cp -n gitconfig ~/.gitconfig
cp -n gitignore ~/.gitignore
cp -Rn git-hooks ~/.git-hooks
```

Be sure not to overwrite existing files or directories (unless you want to).
Update usernames and paths to match your needs.
