# ~/.dotfiles
For tracking my dotfiles on Arch Linux. It's really simple and basic, nothing fancy.

Based on [this thread](https://news.ycombinator.com/item?id=11071754) on Hacker News. And [this post](https://www.atlassian.com/git/tutorials/dotfiles) on atlassian. This approach allows tracking the dotfiles in `$HOME` without having to copy and paste them inside `~/.dotfiles` and manually symlink all of them.

My dotfiles are located at `$HOME/.dotfiles`. The config files are managed using the following alias:
```bash
alias dotfiles='/usr/bin/git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME'
```
I also added this to `~/.zshrc`.

Tracking my [neovim configurations](https://github.com/maqnitude/nvim-init.lua) as a submodule. 
