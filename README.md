# HentaiOS #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/HentaiOS-Exynos9810/platform_manifest -b TwistedScarlett

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
