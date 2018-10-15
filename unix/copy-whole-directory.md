# Copy whole directory

Copying a whole directory is easy with 

```bash
$ cp -rf /source/ /destination/
```

One potential gotcha is the use of the `-f` force flag. This says that if the existing destination file cannot be opened, remove it, and try it again. It's key to bear this in mind because you might not want (or want) to do this, based on whether you want to know if something will work or not.

If this is not the intended behaviour, remove the force flag and simply copy recursively.