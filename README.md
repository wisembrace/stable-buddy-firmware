# StableBuddy firmware releases

This repo holds the release images and manifests for StableBuddy units. It holds no source code.

The units fetch `releases/latest/download/manifest.json`. The manifest names the images for the Base and the Target, with their sizes and SHA-256 values.

Each release also holds the user guide, `user-guide.pdf`. Open the latest one from the [latest release](https://github.com/wisembrace/stable-buddy-firmware/releases/latest).

Releases whose notes start with `TEST:` are bench tests. Their images cannot install on the units in service, and they are deleted after the test.
