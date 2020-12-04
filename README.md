# Configuration files for manifold computers.

This repository contains files that are useful when working with
manifold computers (computers mounted on a drone). These specific files
are made for ROS Kinetic, but can be easily adapted to other version, by
simply changing the `$ROS_DIR environment` variable in `/bash/bashrc`.

## Quickstart Guide

```cd`
git clone git@github.com:immersive-command-system/ISAACS-config.git
git clone https://github.com/junegunn/fzf.git ~/ISAACS-config/fzf
cd ~/ISAACS-config
./fzf/install
mv $HOME/.bashrc $HOME/.bashrc_bkp`
[[ -e $HOME/.tmux.conf ]] && mv $HOME/.tmux.conf $HOME/.tmux_bkp
ln -sv ~/ISAACS-config/bash/bashrc $HOME/.bashrc
ln -sv ~/ISAACS-config/tmux.conf $HOME/.tmux.conf```


## Reinstalling the DJI SDK on the M210

`remake_sdk`
