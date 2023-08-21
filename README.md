# .dotfiles
For managing my dotfiles on Arch Linux. 

Based on this [thread](https://news.ycombinator.com/item?id=11071754) on Hacker News. And this [post on atlassian](https://www.atlassian.com/git/tutorials/dotfiles).

My dotfiles are located at `$HOME/.dotfiles`. The config files are managed using the following alias:
```bash
alias dotfiles='/usr/bin/git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME'
```
I also added this to `~/.zshrc`.

Still working on the neovim, gonna track it as a git module. 
