# f5m-rime-arm64-extra

Prebuilt **fcitx5-rime** plugin binaries for **[fcitx-contrib/fcitx5-macos](https://github.com/fcitx-contrib/fcitx5-macos) arm64**, (maybe)including patches from unmerged PRs.

## Features

- Automated build via GitHub Actions, triggered periodically  
- Built from the latest commit of [fcitx-contrib/fcitx5-plugins](https://github.com/fcitx-contrib/fcitx5-plugins) **at the time of compilation**  
- (maybe)Includes additional patches from unmerged PRs  
- Release assets are stripped binaries for smaller size

## Download

Go to the [Releases](../../releases) page and download the so file.

## Notes

- The build artifacts are generated automatically.  
- Each release asset includes the commit ID of `fcitx5-plugins` used for the build.  
- No manual support is provided — use at your own risk.

## Installation (Optional)

Extract the archive and copy the plugin to your Fcitx5 data directory, e.g.:  

```bash
cp librime.so /<target-path>/
