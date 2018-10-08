# Apply gitignore on existing repository where files are already tracked

Make sure you've already committed all pending changes. Once you're sure that there are no unstaged changes, run this command:

```bash
$ git rm -r --cached .
```

This will remove everything from the index, leaving you to re-add it back in using:

```bash
$ git add .
```

This will re-add everything you removed, except what is mentioned in your `.gitignore` file.