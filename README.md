My tmux configuration. Nothing fancy.

## Setup

### Install tpm
```
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

### Symlink configuration

1) Navigate to the directory where you've cloned the repository.
```
cd /path/to/cloned/repo
```

2) Backup existing tmux configuration just in case
```
mv ~/.tmux.conf ~/.tmux.conf.backup
```

3) Create symbolic links
```
ln -s $(pwd)/tmux.conf ~/.tmux.conf
ln -s $(pwd)/tmux.conf.linux ~/.tmux.conf.linux
```
