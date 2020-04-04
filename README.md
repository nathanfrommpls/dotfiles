# Nate's dotfiles

A collection of dotfiles used to configure my preferred working environment on Unix-like systems. This is currently linux-centric but should be easily adapted for other systems.

Tested on Ubuntu 19.10

## Prerequisites

### Packages

- openbox
- rxvt-unicode
- emacs
- suckless-tools
- conky
- pavucontrol

## Installation

- .xsessionrc should be copied to ~/
- .Xresources.local should be copied to ~/
- ./openbox/ should be copied to ~/.config
- ./conky/ should be copied to ~/.config

## Configuration

./conky/conky.conf may need to be updated to specify the correct devices:
- network interfaces, find names with `ip addr sh`
- battery, find at /sys/class/power_supply/BAT*
- cpu count, find with `lscpu` or `top`

## References

[Solarized](https://ethanschoonover.com/solarized/)
[Conky Varibles](http://conky.sourceforge.net/variables.html)
