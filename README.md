# dotfiles

Inspired by Matthias Bynens dotfiles: https://github.com/mathiasbynens/dotfiles

Guide: https://code.tutsplus.com/tutorials/setting-up-a-mac-dev-machine-from-zero-to-hero-with-dotfiles--net-35449

## Usage

1. Open terminal
2. cd to dotfiles repo and run:
```
source bootstrap.sh
```

Git-free installation: 
```
cd; curl -#L https://github.com/mathiasbynens/dotfiles/tarball/master | tar -xzv --strip-components 1 --exclude={README.md,bootstrap.sh,.osx,LICENSE-MIT.txt}
```
