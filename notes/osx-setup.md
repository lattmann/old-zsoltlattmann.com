---
layout: "default"
title: OSX setup
note: true
categories: [osx, shell, script]
desc: "Install a set of tools on a new OSX machine."
---

[Home page](/)

# Configuration

- Change user password
- Change trackpad settings
- Change dock settings
- Setup fingerprint if applicable
- Sign in to App Store
- Sign in to iTunes
- Sign in to iCloud

# Tools

- [Oh-My-Zsh](http://ohmyz.sh/)
- [Homebrew](https://brew.sh/)
```bash
brew install node mongodb mysql nginx postgresql haproxy
```
- Nodemon
```bash
npm install -g nodemon
```
- MacTex
```bash
brew cask install mactex
```
- [Google Drive](https://www.google.com/drive/download/)
- [Google Chrome](https://www.google.com/chrome/browser/desktop/index.html)
- [Flux](https://justgetflux.com/)
- [Docker Toolbox](https://www.docker.com/products/docker-toolbox)
- [Atom](https://atom.io/)
```bash
apm install nuclide
```

# Configuration

- [vimrc](https://github.com/amix/vimrc)
- Copy private and public key into `~/.ssh` folder
- Update public key on GitHub and BitBucket if required.
- Create ssh config


# Clone git repositories
## GitHub

```bash
pushd .
mkdir ~/Documents/GitHub
cd ~/Documents/GitHub

git clone git@github.com:lycophron/lycophron.git
git clone git@github.com:lycophron/old.lycophron.git
git clone git@github.com:lycophron/lycophron.org.git
git clone git@github.com:lycophron/lycophron.github.io.git

git clone git@github.com:lattmann/lycophron-app.git
git clone git@github.com:lattmann/zsoltlattmann.com.git

git clone git@github.com:webgme/webgme.git

popd
```

## Bitbucket

```bash
pushd .
mkdir ~/Documents/BitBucket
cd ~/Documents/BitBucket
git clone git@bitbucket.org:lattmann/scr.git
git clone git@bitbucket.org:lattmann/cv.git
git clone git@bitbucket.org:lattmann/dissertation.git
popd
```
