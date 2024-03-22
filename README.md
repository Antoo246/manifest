# Anto AOSP #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/Antoo246/manifest -b fourteen

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

