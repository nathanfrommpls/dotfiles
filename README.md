# Nate's dotfiles

Tested on Ubuntu 19.10

## Prerequisites

### Packages

- openbox
- emacs
- suckless-tools
- conky

## Installation

- .xsessionrc should be copied to ~/
- .Xresources.local should be copied to ~/
- ./openbox/ should be copied to ~/.config
- ./conky/ should be copied to ~/.config

## Configuration

./conky/conky.conf may need to be updated to specify the correct devices:
- network interfaces, find names with `ip addr sh`
- battery, find at /sys/class/power_supply/BAT*
- cpu count, find 

## References

[Conky Varibles](http://conky.sourceforge.net/variables.html)
