# inso-pkg

## How to build

```
# Go to insomina-inso directory
cd <path to inso: typically ./node_modules/insomnia-inso>

# Re-package inso
pkg -t node12-linux -o inso .

# Compress it
tar -zcvf insomnia-inso-2.2.35.tar.gz inso
```
