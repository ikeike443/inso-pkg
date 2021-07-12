# inso-pkg

## How to build
```
# Go to insomina-inso directory
cd <path to inso: typically ./node_modules/insomnia-inso>

# Add below to Package.json of insomnia-inso (temporarily for now)
To make sure every node_modules will be included when compiled
  ...
  "pkg": {
        "assets": "node_modules/**/*"
  },
  ...

# Re-package inso
pkg -t node12-linux -o inso .

# Compress it
tar -zcvf insomnia-inso-2.2.35.tar.gz inso
```
