# Pop!_OS 24.04 Setup with Ansible

This repository contains an Ansible playbook to automate the setup of a Pop!_OS 24.04 system with all the necessary software, configurations, and tools I use for development and daily tasks.

## Features

- **System Setup**:
  - Enables the Universe repository.
  - Installs essential packages (e.g. `git`, `neovim`, `zsh`, `tmux`, etc.).
  - Sets up WezTerm, Fastfetch, and other tools.
  - Configures `fcitx5` with Rime for Simplified Chinese input.

- **Development Tools**:
  - Installs `pyenv` and `nvm` for Python and Node.js version management.
  - Includes build dependencies for `pyenv`.

- **Dotfiles Integration**:
  - Clones and sets up my [dotfiles repository](https://github.com/aileks/dotfiles.git), which includes configurations for `dwm`, `oh-my-zsh`, and more.

- **Desktop Environment**:
  - Creates a session desktop file for `dwm`.

- **Third-Party Software**:
  - Installs JetBrains Toolbox, Anki, Brave Browser, and Discord.

## Prerequisites

- **Pop!_OS 24.04**: The playbook is designed for Pop!_OS 24.04 but can be adapted for other Ubuntu-based distributions.
- **Ansible**: Ensure Ansible is installed on your system.

```bash
sudo apt update
sudo apt install ansible
```
