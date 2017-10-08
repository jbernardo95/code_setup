.dotfiles
==========

In this repo you will find the packages/applications I use in macOS, along with their configurations.

## Install 

Start by downloading the repo:

```
$ cd  ~/
$ git clone git@github.com:jbernardo95/.dotfiles.git
$ cd .dotfiles
```

### Packages/Applications

To install all the packages and applications:

```
$ brew bundle 
```

Third party applications listed [here](third_party.md) can not be installed automatically, so you need to go and get them by hand. 

### Configurations

To setup all the configurations follow these steps:

1. Symlink dotfiles: `sh symlink.sh`
2. Install [oh my zsh](https://github.com/robbyrussell/oh-my-zsh)
3. Install [Vundle](https://github.com/VundleVim/Vundle.vim), open *vim* and run `:PluginInstall`
4. Install atom packages `apm install --packages-file atom/package.list`
5. In *iTerm* go to Preferences > Select `Load preferences from a custom folder or URL` to load from `~/.iterm`
6. Setup *macOS* configurations according to [this](config/mac_os.md)
7. Setup *Alfred* configurations according to [this](config/alfred.md)
8. Setup *Spectacle* configurations according to [this](config/spectacle.md)
9. Setup security configurations according to [this](config/security.md)

## Extras

The base `Vagrantfile` I use in my project is available [here](Vagrantfile).
