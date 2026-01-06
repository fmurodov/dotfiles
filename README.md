# Dotfiles

Personal macOS configuration and development environment setup.

## Quick Start

### Prerequisites

- macOS
- [Homebrew](https://brew.sh/)

### Installation

```bash
# Clone repository
git clone git@github.com:fmurodov/dotfiles.git ~/.dotfiles
cd ~/.dotfiles

# Link Brewfile
ln -sf ~/.dotfiles/Brewfile ~/.Brewfile

ln -sf ~/.dotfiles/.config/ghostty/config ~/.config/ghostty/config
ln -sf ~/.dotfiles/.config/zed/settings.json ~/.config/zed/settings.json

# Install packages
brew bundle --global
```

## Usage

**Install/update packages:**
```bash
brew bundle --global
```

**Cleanup unlisted packages:**
```bash
brew bundle cleanup --global
```

## What's Included

All packages documented in [Brewfile](Brewfile):
- Command line tools and utilities
- Development environments and DevOps tools
- Desktop applications
- macOS enhancements

## Resources

- [Homebrew Documentation](https://docs.brew.sh/)
- [Homebrew Bundle](https://docs.brew.sh/Brew-Bundle-and-Brewfile)
