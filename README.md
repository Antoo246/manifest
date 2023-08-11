# Pixel Experience #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/Antoo246/manifest -b thirteen-plus

# Sync
repo sync -c -j$(nproc --all)  --force-sync --no-clone-bundle --no-tags
```

