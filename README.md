# Overview

## Useful commands

List all global installed packages
```bash
npm list -g --depth=0
```

## Shell scripts

Open chrome without security mode
```bash
function chrome() {
  open - a Google\ Chrome --args --disable-web-security --allow-file-access-from-files --user-data-dir
}
```
