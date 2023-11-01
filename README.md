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

In this directory:

2) Create symbolic links
```
ln -s tmux.conf ~/.tmux.conf
ln -s tmux.conf.linux ~/.tmux.conf.linux
```
