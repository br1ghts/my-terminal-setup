# 🚀 Legendary Zsh Terminal Setup

This script provides a quick, straightforward, and epic setup for Zsh with Oh My Zsh, the super-slick Powerlevel10k theme, and handy plugins to level up your command-line game. 

## ✨ What's Included:
- **Oh My Zsh**: The most popular Zsh framework.
- **Powerlevel10k**: A lightning-fast, highly customizable theme.
- **Plugins**:
  - `git`: Git shortcuts for productivity.
  - **zsh-syntax-highlighting**: Highlights commands and syntax.
  - **zsh-autosuggestions**: Smart command autosuggestions.

## 🛠️ Installation (Linux/WSL):

Simply run this script in your terminal:

```bash
chmod +x setup-zsh.sh
./setup-zsh.sh
```

## 🛠️ Installation (macOS):

Install Homebrew dependencies first if needed:

```bash
brew install zsh git wget curl
brew install font-hack-nerd-font
```

Then run the script:

```bash
chmod +x setup-zsh.sh
./setup-zsh.sh
```

## 🚀 Post-Installation:

- Restart your terminal to apply all changes.
- If Powerlevel10k prompts for configuration, simply follow the interactive setup.
- Ensure you've selected **Monaspace** or another Nerd Font in your terminal for the best visuals.

## 📦 Backing Up via Git:

Include this script alongside your `.zshrc` in a git repository to easily backup and restore your Zsh setup:

```bash
git add setup-zsh.sh zshrc
git commit -m "Legendary Zsh terminal setup 🚀"
git push origin main
```

## 🎯 Compatibility:
- ✅ Ubuntu/Debian
- ✅ WSL (Windows Subsystem for Linux)
- ✅ macOS (with minor modifications: ensure Homebrew is installed)

Enjoy your badass, hacker-approved terminal setup, mate! 🌌⚡️👾
