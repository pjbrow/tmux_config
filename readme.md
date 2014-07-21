#TMUX Config for OSX and Linux

This file is placed in `.tmux` on both systems.  It is imported and used by both systems from `~/.tmux.conf`, which should have in it the command `source ~/.tmux/.tmux.conf`.

On Ubuntu, the command `set -g default-terminal "screen-256color"` also needs to go into `~/.tmux.conf`, since the command does not seem to get applied if you source the tmux config from another folder.
