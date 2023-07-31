# sd-fuse_manifests
## How to use
Firstly you need to install the repo utility:
```
wget 'https://storage.googleapis.com/git-repo-downloads/repo' -P /tmp/
sudo cp /tmp/repo /usr/local/bin/repo
sudo chmod +x /usr/local/bin/repo
```
Here you go:
```
mkdir sd-fuse_all
cd sd-fuse_all
repo init -u https://github.com/friendlyarm/sd-fuse_manifests -b master -m all.xml --no-clone-bundle
repo sync -c  --no-clone-bundle
```
