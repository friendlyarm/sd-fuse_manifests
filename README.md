# sd-fuse_manifests
## How to use
Firstly you need to install the repo utility:
```
git clone https://github.com/friendlyarm/repo
sudo cp repo/repo /usr/bin/
```
Here you go:
```
mkdir sd-fuse_all
cd sd-fuse_all
repo init -u https://github.com/friendlyarm/sd-fuse_manifests -b master -m all.xml --repo-url=https://github.com/friendlyarm/repo  --no-clone-bundle
repo sync -c  --no-clone-bundle
```
