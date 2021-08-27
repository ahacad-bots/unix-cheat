

### delete all executables

```bash
find . -maxdepth 1 -type f -executable -exec rm {} +
# or 
find . -maxdepth 1 -type f -executable -delete
```

### copy big file

```bash
split -b 1G file.local filexfer
cat filexfer* > file.remote
```

### list all the fonts

```bash
fc-list
```
