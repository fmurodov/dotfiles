##############################################################
# ~/.Brewfile - macOS Package Management                    #
# Usage: brew bundle --global                                #
# Cleanup: brew bundle cleanup --global                      #
# Repo: https://github.com/fmurodov/dotfiles                 #
##############################################################

# Options
cask_args appdir: '/Applications'

# Taps
tap 'siderolabs/tap'
tap "fluxcd/tap"

# Mac App Store CLI
brew 'mas'

#############################################################
# Command Line Tools                                        #
#############################################################

# Shell & Terminal
brew 'fish'         # Modern shell
brew 'tmux'         # Terminal multiplexer

# Core Utils
brew 'bat'          # Better cat with syntax highlighting
brew 'fzf'          # Fuzzy finder
brew 'jq'           # JSON processor
brew "midnight-commander" # Visual file manager
brew 'rsync'        # File transfer
brew 'tree'         # Directory visualization
brew 'watch'        # Periodic command execution
brew 'yq'           # YAML processor
brew "pipx"

# Monitoring
brew 'bmon'         # Bandwidth monitor
brew 'gping'        # Interactive ping
brew 'speedtest-cli' # Network speed test
#brew 'ctop'        # Container metrics
#brew 'goaccess'    # Web log analyzer

# Productivity
brew 'asciinema'    # Terminal recording
brew 'fastfetch'    # System info
brew 'rclone'       # Cloud storage sync
#brew 'exiftool'    # EXIF metadata editor
#brew 'figlet'      # ASCII art text
#brew 'lolcat'      # Rainbow output
#brew 'neofetch'    # System info (alternative)
#brew 'pipes-sh'    # Screensaver
#brew 'pv'          # Pipe viewer

#############################################################
# Development                                               #
#############################################################

# Version Control & Git
brew 'git'
brew 'gh'           # GitHub CLI
brew 'lazygit'      # Git TUI
#brew 'git-extras'  # Git utilities

# Languages
brew 'go'
brew 'python'
#brew 'gcc'         # C/C++ compiler

# Containers & Orchestration
brew 'docker'
brew 'docker-compose'
brew 'kubernetes-cli'
brew 'lazydocker'   # Docker TUI
brew 'podman'
brew 'podman-compose'
brew 'talosctl'     # Talos Kubernetes CLI
cask 'podman-desktop'
brew "podman-tui"
#brew 'kdash'       # Kubernetes TUI

# DevOps
brew 'ansible'
brew 'cloudflared'  # Cloudflare Tunnel

# API & HTTP
brew 'curlie'       # HTTP client
cask 'bruno'        # API testing

# Editors & IDEs
cask 'ghostty'      # Terminal emulator
cask "kitty"
cask 'visual-studio-code'
cask 'zed'
#brew 'neovim'
cask "arduino-ide"

# Database
cask 'tableplus'    # Database GUI

# Kubernetes
cask 'freelens'     # Kubernetes IDE
brew "stern"
brew "fluxcd/tap/flux"
brew "kubecm"
brew "kubeconform"
brew "kubectx"
brew "kustomize"

# Network & Security
brew 'nmap'         # Port scanner
cask 'wireshark-app'# Network analyzer
#brew 'bettercap'   # Network scanner

# Security & Encryption
#brew 'bcrypt'      # Encryption
#brew 'git-crypt'   # Git encryption
#brew 'openssl'     # SSL/TLS toolkit
#cask 'gpg-suite'   # PGP encryption

#############################################################
# Desktop Applications                                      #
#############################################################

# Productivity
cask '1password' if Socket.gethostname == "fmurodov-pro"
cask 'raycast', args: { require_sha: false } # Launcher

# Communication
cask "discord"
cask 'slack' if Socket.gethostname == "fmurodov-pro"
cask 'telegram'
cask 'whatsapp'
cask 'zoom'
#cask 'signal'      # Encrypted messenger

# Browsers
cask 'chromium'
cask 'comet'        # AI-powered browser
cask 'firefox'
cask 'google-chrome'

# Networking
cask 'tailscale-app'  # VPN mesh network
#cask 'mountain-duck' # Cloud storage mounter

# Utilities
cask 'keka'         # Archive manager
cask "balenaetcher"
cask "raspberry-pi-imager"

# Creative
#cask 'audacity'    # Audio editor
cask "bambu-studio"
#cask 'gimp'        # Image editor
#cask 'inkscape'    # Vector graphics
#cask 'obs'         # Screen recording
#brew 'handbrake'   # Video transcoder
#cask 'shotcut'     # Video editor

#############################################################
# macOS Enhancements                                        #
#############################################################

# System Tools
brew 'iproute2mac'  # Linux-style networking commands

# Window Management
#brew 'yabai'       # Tiling window manager
#brew 'skhd'        # Hotkey daemon

# Menubar
#cask 'anybar'      # Programmable menubar icons
#cask 'hiddenbar'   # Hide menubar icons
#cask 'stats'       # System monitor

# Utilities
#cask 'espanso'     # Text expander
#brew 'lporg'       # Launchpad backup
#brew 'm-cli'       # macOS management CLI
#cask 'openinterminal' # Terminal from Finder
#cask 'santa'       # Binary authorization
#cask 'shottr'      # Screenshot tool
#cask 'coteditor'   # Text editor
#cask 'little-snitch' # Firewall

# Quick Look Plugins
#cask 'qlcolorcode'    # Code with syntax
#cask 'qlimagesize'    # Image dimensions
#cask 'qlmarkdown'     # Markdown files
#cask 'qlprettypatch'  # Patches/diffs
#cask 'qlstephen'      # Plain text files
#cask 'qlvideo'        # Video previews
#cask 'quicklook-csv'  # CSV files
#cask 'quicklook-json', args: { require_sha: false } # JSON
#cask 'quicklookapk', args: { require_sha: false }   # APK files
#cask 'webpquicklook', args: { require_sha: false }  # WebP images

# Fonts
#tap 'homebrew/cask-fonts'
#cask 'font-fira-code'
#cask 'font-hack'
#cask 'font-inconsolata'
#cask 'font-meslo-lg-nerd-font'

# Visual Studio Code
vscode "aaron-bond.better-comments"
vscode "adamhartford.vscode-base64"
vscode "bbenoist.vagrant"
vscode "bierner.markdown-mermaid"
vscode "davidanson.vscode-markdownlint"
vscode "docker.docker"
vscode "donjayamanne.githistory"
vscode "eamodio.gitlens"
vscode "foxundermoon.shell-format"
vscode "github.vscode-github-actions"
vscode "gitlab.gitlab-workflow"
vscode "golang.go"
vscode "hashicorp.terraform"
vscode "ibm.output-colorizer"
vscode "kamikillerto.vscode-colorize"
vscode "keesschollaart.vscode-home-assistant"
vscode "korekontrol.saltstack"
vscode "mads-hartmann.bash-ide-vscode"
vscode "marcostazi.vs-code-vagrantfile"
vscode "mechatroner.rainbow-csv"
vscode "mikestead.dotenv"
vscode "moshfeu.compare-folders"
vscode "ms-azuretools.vscode-containers"
vscode "ms-azuretools.vscode-docker"
vscode "ms-kubernetes-tools.vscode-kubernetes-tools"
vscode "ms-python.python"
vscode "ms-vscode-remote.remote-containers"
vscode "ms-vscode-remote.remote-ssh"
vscode "ms-vscode-remote.remote-ssh-edit"
vscode "ms-vscode.cmake-tools"
vscode "ms-vscode.cpptools"
vscode "ms-vscode.cpptools-extension-pack"
vscode "ms-vscode.cpptools-themes"
vscode "ms-vscode.hexeditor"
vscode "ms-vscode.makefile-tools"
vscode "ms-vscode.remote-explorer"
vscode "quicktype.quicktype"
vscode "redhat.java"
vscode "redhat.vscode-yaml"
vscode "tatsy.vscode-3d-preview"
vscode "timonwong.shellcheck"
vscode "weaveworks.vscode-gitops-tools"
vscode "zainchen.json"

# EOF
