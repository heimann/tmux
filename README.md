My tmux configuration. Nothing fancy.

## Setup

### Install tpm
```
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

### Symlink configuration

1) Backup existing tmux configuration just in case
```
mv ~/.tmux.conf ~/.tmux.conf.backup
```

2) Create symbolic links
```
ln -s /home/david/.tmux-conf/tmux.conf ~/.tmux.conf
ln -s /home/david/.tmux-conf/tmux.conf.linux ~/.tmux.conf.linux
```
