# dot_git
My Git config

## Installation
### Manual installation
This repository is prepared to be used together with gnu stow. See [Brandon Invergo's
explanation](http://brandon.invergo.net/news/2012-05-26-using-gnu-stow-to-manage-your-dotfiles.html)
on how to use it. In short

```
mkdir ~/dotfiles
cd ~/dotfiles
git clone --recurse-submodules https://github.com/fmauch/dot_git.git
stow dot_git
```
This will create symliks for the dotfiles specified in ```dot_git``` relative to your home folder.
