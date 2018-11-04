# avfirmware_manifest

This project is the repo manifest repository for my collection of projects for Avionics Firmware.
[repo](https://gerrit.googlesource.com/git-repo) is the tool used in Android to manage the git repositories for that project.

## Getting Started

* Obtain [repo](https://source.android.com/setup/build/downloading)
* Add the repo script to your path
* Create a directory and initialize a repo project in that directory
```
mkdir avfirmware
chdir avfirmware
repo init -u https://github.com/gpgreen/avfirmware_manifest
```
* Synchronize the source to your computer
```
repo sync
```

## Selecting different firmware build configurations

TODO