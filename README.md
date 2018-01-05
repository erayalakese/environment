# Install MSYS2

1. Download and install from http://www.msys2.org/
1. Install updates with `pacman -Syu`
1. `pacman -Sy msys2-runtime bash pacman git curl vim nano zsh`
1. Open `msys2_shell.cmd` (C:\msys64) and replace all `/usr/bin/bash` to `/usr/bin/zsh`
1. Add this to USER ENVIRONMENT VARIABLES in order to use Windows env. vars. `MSYS2_PATH_TYPE=inherit`

# Oh-My-Scan

`sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

# Solarized Dark Theme

1. Copy `solarized.dark` file to home directory
1. `cat solarized.dark >> .zshrc`
