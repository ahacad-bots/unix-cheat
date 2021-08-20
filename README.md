


### Copy big file

```bash
split -b 1G file.local filexfer
cat filexfer* > file.remote
```
