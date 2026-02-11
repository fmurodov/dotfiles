##############################################################
# ~/Brewfile - macOS Package Management                    #
# Usage: brew bundle --global                                #
# Cleanup: brew bundle cleanup --global                      #
# Repo: https://github.com/fmurodov/dotfiles                 #
##############################################################

# Options
COMPUTER_NAME = `scutil --get LocalHostName`.strip
cask_args appdir: '/Applications'

# Taps
tap 'siderolabs/tap'
tap 'fluxcd/tap'
tap 'slp/krunkit'

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
brew 'midnight-commander' # Visual file manager
brew 'rsync'        # File transfer
brew 'tree'         # Directory visualization
brew 'watch'        # Periodic command execution
brew 'yamllint'     # YAML linter
brew 'yq'           # YAML processor
brew 'pipx' if COMPUTER_NAME == 'fmurodov-macbookair' # Python package installer

# Monitoring
brew 'bmon'         # Bandwidth monitor
brew 'gping'        # Interactive ping
brew 'speedtest-cli' # Network speed test
#brew 'ctop'        # Container metrics
#brew 'goaccess'    # Web log analyzer

# Productivity
brew 'asciinema'    # Terminal recording
brew 'difftastic'   # Diff that understands syntax
brew 'fastfetch'    # System info
brew 'rclone'       # Cloud storage sync
#brew 'exiftool'    # EXIF metadata editor
#brew 'figlet'      # ASCII art text
#brew 'lolcat'      # Rainbow output
#brew 'neofetch'    # System info (alternative)
#brew 'pipes-sh'    # Screensaver
#brew 'pv'          # Pipe viewer
bews 'shellcheck'   # shell linter
#############################################################
# Development                                               #
#############################################################

# Version Control & Git
brew 'git'
brew 'gh'           # GitHub CLI
brew 'glab'         # GitLab CLI
brew 'lazygit'      # Git TUI
#brew 'git-extras'  # Git utilities

# Languages
brew 'go'
brew 'python'
brew 'gcc'          # C/C++ compiler
brew 'cmake'        # CMake build system

brew 'ninja'        # Build system
brew 'dfu-util'     # USB programmer

# Containers & Orchestration
brew 'docker'
brew 'docker-compose'
cask 'docker-desktop'
brew 'kubernetes-cli'
brew 'lazydocker'   # Docker TUI
brew 'podman'
brew 'podman-compose'
brew 'slp/krunkit/krunkit' # libkrun vm for podman
brew 'talosctl'     # Talos Kubernetes CLI
brew 'talhelper'    # Configuration helper for talos clusters
cask 'podman-desktop'
brew 'podman-tui'   # Podman terminal UI
#brew 'kdash'       # Kubernetes TUI
brew 'ingress2gateway' # Convert Ingress resources to Gateway API resources
cask 'virtualbox'

# DevOps
brew 'ansible'
brew 'cloudflared'  # Cloudflare Tunnel
brew 'opentofu'     # Infrastructure as Code (Terraform alternative)

# API & HTTP
brew 'curlie'       # HTTP client
cask 'bruno'        # API testing
brew 'wget'         # Download utility

# Editors & IDEs
cask 'ghostty'      # Terminal emulator
cask 'kitty'        # GPU-based terminal emulator
cask 'visual-studio-code'
cask 'zed'
cask 'claude-code'  # AI-powered coding assistant
#brew 'neovim'
cask 'arduino-ide'  # Arduino development IDE

# Database
cask 'tableplus'    # Database GUI

# Kubernetes
brew 'cilium-cli'   # Cilium client
cask 'freelens'     # Kubernetes IDE
brew 'stern'        # Multi-pod log tailing
brew 'fluxcd/tap/flux' # GitOps toolkit
brew 'helm'         # Kubernetes package manager
brew 'k9s'          # Kubernetes CLI
brew 'kubecm'       # Kubeconfig manager
brew 'kubeconform'  # Kubernetes manifest validator
brew 'kubectx'      # Context and namespace switcher
brew 'kustomize'    # Kubernetes configuration customization

# Network & Security
brew 'nmap'         # Port scanner
cask 'wireshark-app'# Network analyzer
#brew 'bettercap'   # Network scanner
cask 'wifiman'      # Network monitoring and troubleshooting

# Security & Encryption
brew 'age'          # Simple, modern, secure file encryption
brew 'gitleaks'     # Git repository security scanner
brew 'git-filter-repo' # Git repository filter
brew 'sops'         # Secrets management
brew 'trivy'        # Vulnerability scanner
#brew 'bcrypt'      # Encryption
#brew 'git-crypt'   # Git encryption
#brew 'openssl'     # SSL/TLS toolkit
cask 'gpg-suite'   # PGP encryption

#############################################################
# Desktop Applications                                      #
#############################################################

# Productivity
cask '1password' if COMPUTER_NAME == 'fmurodov-pro' # Password manager
cask 'raycast', args: { require_sha: false } # Launcher

# Communication
cask 'discord'      # Voice and text chat
cask 'slack' if COMPUTER_NAME == 'fmurodov-pro'
cask 'telegram'
cask 'whatsapp'
cask 'zoom'
#cask 'signal'      # Encrypted messenger

# Browsers
cask 'comet'        # AI-powered browser
cask 'firefox'
cask 'google-chrome'

# Networking
cask 'tailscale-app'  # VPN mesh network
#cask 'mountain-duck' # Cloud storage mounter
mas 'Discovery - DNS-SD Browser', id: 1381004916

# Utilities
cask 'keka'         # Archive manager
cask 'balenaetcher' # USB flash tool
cask 'monitorcontrol' # Monitor brightness control
cask 'raspberry-pi-imager' # Raspberry Pi SD card writer

# Creative
#cask 'audacity'    # Audio editor
cask 'bambu-studio' # 3D printing slicer
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
brew 'subnetcalc'   # Subnet calculator

# Window Management
#brew 'yabai'       # Tiling window manager
#brew 'skhd'        # Hotkey daemon

# Menubar
#cask 'anybar'      # Programmable menubar icons
#cask 'hiddenbar'   # Hide menubar icons
#cask 'stats'       # System monitor
mas 'Itsyhome', id: 6758070650  # menubar HomeKit control

# Utilities
#cask 'espanso'     # Text expander
#brew 'lporg'       # Launchpad backup
#brew 'm-cli'       # macOS management CLI
#cask 'openinterminal' # Terminal from Finder
#cask 'santa'       # Binary authorization
#cask 'shottr'      # Screenshot tool
#cask 'coteditor'   # Text editor
#cask 'little-snitch' # Firewall
cask 'mac-mouse-fix' # Mouse utility to add gesture functions

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

# Visual Studio Code Extensions

# Git & Version Control
vscode 'donjayamanne.githistory'
vscode 'eamodio.gitlens'
vscode 'github.vscode-github-actions'
vscode 'gitlab.gitlab-workflow'

# Containers & Kubernetes
vscode 'docker.docker'
vscode 'ms-azuretools.vscode-containers'
vscode 'ms-azuretools.vscode-docker'
vscode 'ms-kubernetes-tools.vscode-kubernetes-tools'

# Remote Development
vscode 'ms-vscode-remote.remote-containers'
vscode 'ms-vscode-remote.remote-ssh'
vscode 'ms-vscode-remote.remote-ssh-edit'
vscode 'ms-vscode.remote-explorer'

# Languages - Go
vscode 'golang.go'

# Languages - Python
vscode 'ms-python.python'

# Languages - C/C++
vscode 'ms-vscode.cmake-tools'
vscode 'ms-vscode.cpptools'
vscode 'ms-vscode.cpptools-extension-pack'
vscode 'ms-vscode.cpptools-themes'
vscode 'ms-vscode.makefile-tools'

# Languages - Java
vscode 'redhat.java'

# DevOps & Infrastructure
vscode 'hashicorp.terraform'
vscode 'korekontrol.saltstack'
vscode 'weaveworks.vscode-gitops-tools'

# Shell & Scripting
vscode 'foxundermoon.shell-format'
vscode 'mads-hartmann.bash-ide-vscode'
vscode 'timonwong.shellcheck'

# Configuration & Data Formats
vscode 'mechatroner.rainbow-csv'
vscode 'mikestead.dotenv'
vscode 'redhat.vscode-yaml'
vscode 'quicktype.quicktype'
vscode 'zainchen.json'

# Markdown & Documentation
vscode 'bierner.markdown-mermaid'
vscode 'davidanson.vscode-markdownlint'

# Virtualization & Development Tools
vscode 'bbenoist.vagrant'
vscode 'marcostazi.vs-code-vagrantfile'
vscode 'espressif.esp-idf-extension'

# Utilities & Helpers
vscode 'aaron-bond.better-comments'
vscode 'adamhartford.vscode-base64'
vscode 'ibm.output-colorizer'
vscode 'kamikillerto.vscode-colorize'
vscode 'keesschollaart.vscode-home-assistant'
vscode 'moshfeu.compare-folders'
vscode 'ms-vscode.hexeditor'
vscode 'tatsy.vscode-3d-preview'
# EOF
