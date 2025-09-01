# Arch Linux Bootstrap Script
#
# This script is something I originally put together on my
# personal GitHub and am bringing over here for the purpose of 
# showcasing my skills to future employers
#
# It’s meant as a disaster-recovery tool for my Arch Linux setup:
# if something catastrophic happens to my machine, I can run this
# script to quickly restore what I consider essential packages,
# tools, and configurations for my personal device.
#
# It installs:
#   - Core developer utilities (base-devel, Git, Python, compilers)
#   - Everyday CLI tools (fzf, ripgrep, htop, neovim, tmux, etc.)
#   - System services (NetworkManager, PipeWire, Bluetooth, firewall)
#   - Fonts and GUI tools (FiraCode Nerd Font, Brave, feh)
#   - My preferred themes and shell customizations (Chicago95,
#     screenfetch, aliases, Starship prompt)
#   - An AUR helper (paru) for extended package support
#
# The script is designed to be idempotent (safe to re-run) and
# seeds basic dotfiles (.gitconfig, .bash_aliases, .tmux.conf, etc.)
# if they don’t already exist.
#
# This isn’t meant to be a universal Arch installer.
# It’s a personal bootstrap script, tailored to what I consider
# “essentials” on my own machine.
#
# RESULTS MAY VARY
# ------------------------------------------------------------
