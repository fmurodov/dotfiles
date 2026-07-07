# ~/Brewfile — macOS Package Management
# Usage: brew bundle --global
# Cleanup: brew bundle cleanup --global

# Options
COMPUTER_NAME = `scutil --get LocalHostName`.strip
cask_args appdir: '/Applications'

# Taps
tap 'anomalyco/tap', trusted: true    # Opencode
tap 'fluxcd/tap', trusted: true       # Flux CD GitOps toolkit
tap 'siderolabs/tap', trusted: true   # Talos Linux tooling

###########################################################
# Terminal & Shell                                        #
###########################################################

brew 'fish'      # User-friendly command-line shell
brew 'tmux'      # Terminal multiplexer
cask 'ghostty'   # Terminal emulator with native UI and GPU acceleration
cask 'kitty'     # GPU-based terminal emulator

###########################################################
# CLI Tools                                               #
###########################################################

brew 'asciinema'           # Record and share terminal sessions
brew 'bat'                 # cat clone with syntax highlighting and Git integration
brew 'curlie'              # Power of curl, ease of use of httpie
brew 'difftastic'          # Syntax-aware structural diff tool
brew 'fastfetch'           # Fast system info fetcher (neofetch alternative)
brew 'ffmpeg'              # Record, convert, and stream audio and video
brew 'fzf'                 # Command-line fuzzy finder
brew 'jq'                  # Lightweight command-line JSON processor
brew 'mas'                 # Mac App Store command-line interface
brew 'midnight-commander'  # Terminal-based visual file manager
brew 'pipx' if COMPUTER_NAME == 'fmurodov-macbookair' # Run Python CLI tools in isolated envs
brew 'rclone'              # Rsync for cloud storage
brew 'icann-rdap'          # Client for the Registry Data Access Protocol (RDAP)
brew 'rsync'               # Fast incremental file transfer utility
brew 'shellcheck'          # Static analysis and lint tool for shell scripts
brew 'swaks'               # Swiss Army knife for SMTP testing
brew 'tree'                # Display directories as trees
brew 'watch'               # Execute a program periodically, fullscreen output
brew 'wget'                # Internet file retriever
brew 'yamllint'            # Linter for YAML files
brew 'salt-lint'           # Linter for SaltStack
brew 'yq'                  # Process YAML, JSON, XML, CSV from the CLI

###########################################################
# Development                                             #
###########################################################

# Version Control
brew 'git'       # Distributed revision control system
brew 'gh'        # GitHub command-line tool
brew 'glab'      # Open-source GitLab command-line tool
brew 'lazygit'   # Terminal UI for git commands

# Languages & Build
brew 'cmake'     # Cross-platform build system generator
brew 'dfu-util'  # USB programmer for DFU-capable devices
brew 'gcc'       # GNU compiler collection
brew 'go'        # Go programming language
brew 'ninja'     # Small, fast build system
brew 'python'    # Python programming language
brew 'uv'        # Extremely fast Python package manager, written in Rust

# Editors
brew 'neovim'                 # Extensible Vim-fork focused on agility
cask 'arduino-ide'            # Electronics prototyping IDE
cask 'visual-studio-code'     # Open-source code editor by Microsoft
cask 'zed'                    # Multiplayer code editor

# API & Database
cask 'bruno'       # Open-source API explorer and testing IDE
cask 'tableplus'   # Native GUI for relational databases

# AI & LLM
cask 'claude'                                 # Anthropic's official Claude AI desktop app
cask 'claude-code'                            # Anthropic's terminal-based AI coding assistant
cask 'lm-studio'                              # Discover, download, and run local LLMs
cask 'lm-studio'                              # Discover, download, and run local LLMs
brew 'anomalyco/tap/opencode', trusted: true  # Open AI coding agent

###########################################################
# Containers & Kubernetes                                 #
###########################################################

# Docker
brew 'docker'            # Container runtime and toolchain
brew 'docker-compose'    # Define and run multi-container Docker apps
brew 'lazydocker'        # Terminal UI for Docker management
cask 'docker-desktop'    # Docker GUI for building and sharing containers

# Podman
brew 'podman'                  # Daemonless OCI container and pod manager
brew 'podman-compose'          # docker-compose alternative using Podman
brew 'podman-tui'              # Podman terminal user interface
cask 'podman-desktop'          # GUI for browsing and managing containers

# VMs
cask 'virtualbox'   # Virtualizer for ARM64 hardware

# Kubernetes
brew 'cilium-cli'                      # CLI to manage Kubernetes clusters running Cilium
brew 'fluxcd/tap/flux', trusted: true  # GitOps toolkit for Kubernetes (Flux CLI)
brew 'helm'                            # Kubernetes package manager
brew 'ingress2gateway'                 # Convert Ingress resources to Gateway API
brew 'k9s'                             # Terminal UI to manage Kubernetes clusters
brew 'kubecm'                          # Manage and switch between kubeconfigs
brew 'kubeconform'                     # Fast Kubernetes manifest validator
brew 'kubectx'                         # Switch kubectl contexts and namespaces
brew 'kubernetes-cli'                  # Kubernetes command-line tool (kubectl)
brew 'kustomize'                       # Template-free Kubernetes YAML customization
brew 'stern'                           # Tail logs across multiple pods and containers
brew 'talhelper'                       # Configuration helper for Talos clusters
brew 'talosctl'                        # CLI for managing Talos Linux Kubernetes nodes
cask 'freelens'                        # Open-source Kubernetes IDE
cask 'headlamp'                        # Web-based Kubernetes dashboard

###########################################################
# Infrastructure & Security                               #
###########################################################

# DevOps
brew 'ansible'      # Agentless IT automation and configuration management
brew 'cloudflared'  # Cloudflare Tunnel client
brew 'opentofu'     # Open-source Terraform-compatible IaC tool

# Network
brew 'bmon'                                     # Network interface bandwidth monitor
brew 'gping'                                    # Ping with a live graph
brew 'iproute2mac'                              # macOS wrapper for Linux ip commands
brew 'mtr'                                      # Combines traceroute and ping in one tool
brew 'nmap'                                     # Network exploration and port scanner
brew 'speedtest-cli'                            # Speedtest.net bandwidth test from CLI
brew 'subnetcalc'                               # IPv4/IPv6 subnet calculator
cask 'tailscale-app'                            # Mesh VPN based on WireGuard
cask 'wifiman'                                  # Wi-Fi network monitoring tool
cask 'wireshark-app'                            # Network protocol analyzer
mas 'Discovery - DNS-SD Browser', id: 1381004916 # Browse mDNS/DNS-SD services on the network
mas 'WireGuard', id: 1451685025                 # WireGuard VPN client

# Security & Encryption
brew 'age'              # Simple, modern file encryption
brew 'git-filter-repo'  # Rewrite and clean up git repository history
brew 'gitleaks'         # Scan git repos for secrets and credentials
brew 'sops'             # Encrypt and edit secret files
brew 'trivy'            # Vulnerability scanner for containers and filesystems
cask 'gpg-suite'        # GPG tools for encrypting emails and files

###########################################################
# Desktop Apps                                            #
###########################################################

# Productivity
cask '1password' if COMPUTER_NAME == 'fmurodov-pro'     # Password manager
cask '1password-cli' if COMPUTER_NAME == 'fmurodov-pro' # Command-line interface for 1Password
cask 'raycast', args: { require_sha: false }            # Keystroke-driven launcher and productivity tool

# Communication
cask 'discord'                                 # Voice and text chat
cask 'slack' if COMPUTER_NAME == 'fmurodov-pro' # Team messaging and collaboration
cask 'telegram'                                # Fast and secure messaging app
cask 'whatsapp'                                # WhatsApp native desktop client
cask 'zoom'                                    # Video meetings and conferencing

# Browsers
cask 'comet'          # Web browser with integrated AI assistant
cask 'firefox@beta'   # Mozilla Firefox (beta channel)
cask 'google-chrome'  # Google Chrome web browser

# File Management & Storage
cask 'cyberduck'      # FTP, SFTP, and cloud storage browser
cask 'google-drive'   # Google Drive desktop sync client
cask 'keka'           # File archiver and extractor

# System & Input
cask 'mac-mouse-fix'   # Add gestures and smooth scrolling to third-party mice
cask 'monitorcontrol'  # Control external monitor brightness and volume

# Hardware & Imaging
cask 'balenaetcher'         # Flash OS images to SD cards and USB drives
cask 'raspberry-pi-imager'  # Write OS images to microSD for Raspberry Pi
cask 'qflipper'             # Companion app for Flipper Zero devices

# IoT & Protocol
cask 'mqttx'   # Cross-platform MQTT 5.0 desktop client

# Creative & 3D Printing
cask 'bambu-studio'   # 3D slicer maintained by Bambu Lab
cask 'orcaslicer'     # G-code generator for 3D printers

# Other
cask 'xquartz'                        # X11 window system for macOS
mas 'Itsyhome', id: 6758070650        # iOS-style home screen launcher for macOS
mas 'PDFScanner', id: 410968114       # Scan and OCR documents to PDF

###########################################################
# VS Code Extensions                                      #
###########################################################

# Git & Version Control
vscode 'donjayamanne.githistory'       # View git log, file history, and branch diffs
vscode 'eamodio.gitlens'              # Supercharge git — blame, history, and more
vscode 'github.vscode-github-actions'  # GitHub Actions workflow support
vscode 'gitlab.gitlab-workflow'        # GitLab CI/CD and merge request integration

# Containers & Kubernetes
vscode 'docker.docker'                               # Docker container management
vscode 'ms-azuretools.vscode-containers'             # Azure container tools
vscode 'ms-azuretools.vscode-docker'                 # Build, run, and debug containers
vscode 'ms-kubernetes-tools.vscode-kubernetes-tools' # Kubernetes cluster management

# Remote Development
vscode 'ms-vscode-remote.remote-containers'  # Dev Containers support
vscode 'ms-vscode-remote.remote-ssh'         # SSH remote development
vscode 'ms-vscode-remote.remote-ssh-edit'    # Edit remote SSH config files
vscode 'ms-vscode.remote-explorer'           # Remote Explorer panel

# Languages
vscode 'golang.go'                          # Go language support
vscode 'ms-python.python'                   # Python language support
vscode 'ms-vscode.cmake-tools'              # CMake project integration
vscode 'ms-vscode.cpptools'                 # C/C++ IntelliSense and debugging
vscode 'ms-vscode.cpptools-extension-pack'  # C/C++ extension bundle
vscode 'ms-vscode.cpptools-themes'          # C/C++ editor color themes
vscode 'ms-vscode.makefile-tools'           # Makefile support
vscode 'redhat.java'                        # Java language support

# DevOps & Infrastructure
vscode 'hashicorp.terraform'            # Terraform/OpenTofu language support
vscode 'korekontrol.saltstack'          # SaltStack state file support
vscode 'weaveworks.vscode-gitops-tools' # GitOps tools for Flux and ArgoCD

# Shell & Scripting
vscode 'foxundermoon.shell-format'       # Shell/Dockerfile/Makefile formatter
vscode 'mads-hartmann.bash-ide-vscode'   # Bash language server
vscode 'timonwong.shellcheck'            # ShellCheck linter integration

# Configuration & Data Formats
vscode 'mechatroner.rainbow-csv'  # Highlight CSV columns with distinct colors
vscode 'mikestead.dotenv'         # .env file syntax highlighting
vscode 'quicktype.quicktype'      # Paste JSON as typed code in any language
vscode 'redhat.vscode-yaml'       # YAML language support
vscode 'zainchen.json'            # Enhanced JSON viewer and tools

# Documentation
vscode 'bierner.markdown-mermaid'       # Mermaid diagram preview in Markdown
vscode 'davidanson.vscode-markdownlint' # Markdown linting and style checking

# Embedded & Virtualization
vscode 'bbenoist.vagrant'               # Vagrant file syntax highlighting
vscode 'espressif.esp-idf-extension'    # ESP-IDF framework for ESP32 development
vscode 'marcostazi.vs-code-vagrantfile' # Vagrantfile syntax and snippets

# Utilities
vscode 'aaron-bond.better-comments'            # Color-code comment annotations by type
vscode 'adamhartford.vscode-base64'            # Base64 encode/decode tool
vscode 'ibm.output-colorizer'                  # Syntax highlighting for output panels
vscode 'kamikillerto.vscode-colorize'          # Visualize CSS/hex colors inline
vscode 'keesschollaart.vscode-home-assistant'  # Home Assistant config support
vscode 'moshfeu.compare-folders'               # Compare and sync two folder trees
vscode 'ms-vscode.hexeditor'                   # Hex editor for binary files
vscode 'tatsy.vscode-3d-preview'               # Preview 3D model files (STL, OBJ, etc.)
