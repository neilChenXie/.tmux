# Tmux

work like screen, but more powerful.

## Prerequest

1. `/etc/profile`

```bash
$:echo `echo $TERM`-256color
# add to Support 256 color
export TERM={output_result}
```

2. libevent

```bash
tar -zxvf {package}
./configure && make
sudo make install
```
## Install

```bash
# download
./configure && make
sudo make install
```

```bash
ln -s ~/.tmux/tmux.conf ~/.tmux.conf
```

## Ref

* [tmux.conf](https://github.com/hatoishi/dotfiles/blob/master/tmux.conf)

# Useful Tool

* [tmuxinator](https://github.com/tmuxinator/tmuxinator)
* [tumxinator completion bash](https://github.com/tmuxinator/tmuxinator/blob/master/completion/tmuxinator.bash)

## Bug

* [freeze](http://superuser.com/questions/553330/vim-freezes-inside-tmux)
