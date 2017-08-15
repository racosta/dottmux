# dottmux
The intention of this repository is to store my tmux configuration for all
platforms in one place with a unified configuration.  I'm starting with my
configuration from my Linux profile and will customize it so that it will
also work correctly with Cygwin.

# Installation:

    git clone https://github.com/racosta/dottmux.git ~/.tmux

## Create symlinks:

    ln -sf ~/.tmux/tmux.conf ~/.tmux.conf

## Switch to the `~/.tmux` directory, and fetch submodules:

    cd ~/.tmux/
    git submodule init
    git submodule update

# Configuration contents:

## Plugins

 - tpm - Tmux Plugin Manager
 - Tmux Prefix Highlight
 - Tmux Sensible
 - Tmux Sidebar
 - Tmux Colors Solarized

## Status bar "airline"

Following [Make your TMux status bar responsive](https://coderwall.com/p/trgyrq/make-your-tmux-status-bar-responsive)
I configured my status bar to call an external script in `~/.tmux/bin/` which
will alter the status line depending on the screen width.  I may come back to
this later.
