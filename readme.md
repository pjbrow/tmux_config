#TMUX Config for OSX and Linux

This file is placed in `.tmux` on both systems.  It is imported and used by both systems in `~/.tmux.conf`.

On Ubuntu, `set -g default-terminal "screen-256color"` also needs to go into `~/.tmux.conf` since the command does not seem to get applied if you source the tmux config from another folder.
