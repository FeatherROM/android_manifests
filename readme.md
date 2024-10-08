# Feather ROM

To initialize the manifest, make sure that you've added and configured your SSH key/connection for [github.com](https://docs.github.com/en/authentication/connecting-to-github-with-ssh "github.com") and [gitlab.com](https://docs.gitlab.com/ee/user/ssh.html "gitlab.com"). Then execute the following commands:

```shell
repo init -u git@github.com:FeatherROM/android_manifests.git -b 15 --git-lfs
```
```shell
repo sync --no-tags --no-clone-bundle --optimized-fetch --prune -c
```

This will sync the source, and you can start compilation after that. If you need help, check the reference device tree at [android_device_xiaomi_tapas](https://github.com/FeatherROM/android_device_xiaomi_tapas "android_device_xiaomi_tapas").
