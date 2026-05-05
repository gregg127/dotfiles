Requirements:

- installed tmux
- installed https://github.com/tmux-plugins/tpm

Tmux conf file should reside:

- Ubuntu: `~/.tmux.conf`

Clone repo:

```bash
cd ~ && git clone https://github.com/gregg127/dotfiles
```

Create symlink:

```bash
ln -s ~/dotfiles/tmux/tmux.conf ~/.tmux.conf
```

Install plugins with tmux opened: "Ctrl + b" then "Shift + I"
