# .dotfiles

Personal collection of configuration files for various programs and systems.

## Installation

Clone the repository to your home directory and then apply or import these configurations.

```bash
$> git clone git@github.com:tmdhkzh/.dotfiles.git
```

## Supported Configurations

### alacritty  
in **~/.alacritty.yml** or **~/.config/alacritty/alacritty.yml**:   
```
import ~/.dotfiles/alacritty/alacritty.yml
```

### bash
in **~/.bashrc**:
```
[ -f $HOME/.dotfiles/bash/bashrc ] && . $HOME/.dotfiles/bash/bashrc
```

### git
in **~./gitconfig**:
```
[include]
	path = ~/.dotfiles/git/gitconfig
```

### tmux  
in **~/.tmux.conf** or **~/.config/tmux/tmux.conf**:   
```
source-file ~/.dotfiles/tmux/tmux.conf
```

### vim  
in **~/.vimrc**:   
```
source ~/.dotfiles/vim/vimrc.vim
```
