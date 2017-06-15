[//]: # (**Focus environment systems/platforms: Windows and/or Linux\(Debian distros\)**)

---
# Installing Git
Before embarking on the basics of Git, install git using the procedure for your operating system (OS). The OSes covered in this guide include Windows, Linux and MacOS.

## Windows
Download the installer from [here](https://git-for-windows.github.io/) and follow the installation wizard.

(Recommended) Download the Git Credential Manager for Windows from [here](https://github.com/Microsoft/Git-Credential-Manager-for-Windows/releases/latest). Be sure to check the [repo](https://github.com/Microsoft/Git-Credential-Manager-for-Windows) for further instructions.

## Mac
Download the latest installer for [git for Mac](https://sourceforge.net/projects/git-osx-installer/) and install through the prompts.

(Recommended)
Download the [Git credential OSX keychain helper](curl -O http://github-media-downloads.s3.amazonaws.com/osx/git-credential-osxkeychain).
Open terminal

```
cd /path/to/credential/helper/download

sudo mv git-credential-osxkeychain /usr/local/bin

chmod u+x /usr/local/bin/git-credential-osxkeychain
```

## Linux
Open terminal. Then follow instructions according to your Linux distribution.

### Ubuntu

```
sudo apt-get update
sudo apt-get install git
```

### Fedora
```
sudo yum install git
```

### OpenSUSE
Install from the [repository](https://software.opensuse.org/package/git). Be sure to select the correct distribution.


