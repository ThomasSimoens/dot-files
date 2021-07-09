# dot-files

This repo contains some of my most common configuration files.

## Setup

Typically these dot-files reside in the home directory, so adding them can be done by:

```bash
cd ~
git init
git remote add origin git@github.com:ThomasSimoens/dot-files.git
git fetch
git checkout -f main
```

## Adding dot-files

Since everything is ignored by git by default (see `.gitignore`),
new files should be added by:

```bash
git add -f $file_name
```
