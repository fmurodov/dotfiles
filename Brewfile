# ~/Brewfile — macOS Package Management
# Usage: brew bundle --global
# Cleanup: brew bundle cleanup --global

# Options
COMPUTER_NAME = `scutil --get LocalHostName`.strip
cask_args appdir: '/Applications'

# Taps
tap 'fluxcd/tap'
tap 'siderolabs/tap'
tap 'slp/krunkit'

###########################################################
# Terminal & Shell                                        #
###########################################################

brew 'fish'
brew 'tmux'
cask 'ghostty'
cask 'kitty'

###########################################################
# CLI Tools                                               #
###########################################################

brew 'bat'
brew 'curlie'
brew 'difftastic'
brew 'fastfetch'
brew 'ffmpeg'
brew 'fzf'
brew 'jq'
brew 'mas'
brew 'midnight-commander'
brew 'pipx' if COMPUTER_NAME == 'fmurodov-macbookair'
brew 'rclone'
brew 'rsync'
brew 'shellcheck'
brew 'tree'
brew 'watch'
brew 'wget'
brew 'yamllint'
brew 'yq'

# Recording
brew 'asciinema'

###########################################################
# Development                                             #
###########################################################

# Version Control
brew 'git'
brew 'gh'
brew 'glab'
brew 'lazygit'

# Languages & Build
brew 'cmake'
brew 'dfu-util'
brew 'gcc'
brew 'go'
brew 'ninja'
brew 'python'
brew 'uv'

# Editors
cask 'arduino-ide'
cask 'claude'
cask 'claude-code'
cask 'visual-studio-code'
cask 'zed'

# API & Database
cask 'bruno'
cask 'tableplus'

###########################################################
# Containers & Kubernetes                                 #
###########################################################

# Docker
brew 'docker'
brew 'docker-compose'
brew 'lazydocker'
cask 'docker-desktop'

# Podman
brew 'podman'
brew 'podman-compose'
brew 'podman-tui'
brew 'slp/krunkit/krunkit'
cask 'podman-desktop'

# VMs
cask 'virtualbox'

# Kubernetes
brew 'cilium-cli'
brew 'fluxcd/tap/flux'
brew 'helm'
brew 'ingress2gateway'
brew 'k9s'
brew 'kubecm'
brew 'kubeconform'
brew 'kubectx'
brew 'kubernetes-cli'
brew 'kustomize'
brew 'stern'
brew 'talhelper'
brew 'talosctl'
cask 'freelens'

###########################################################
# Infrastructure & Security                               #
###########################################################

# DevOps
brew 'ansible'
brew 'cloudflared'
brew 'opentofu'

# Network
brew 'bmon'
brew 'gping'
brew 'iproute2mac'
brew 'nmap'
brew 'speedtest-cli'
brew 'subnetcalc'
cask 'tailscale-app'
cask 'wifiman'
cask 'wireshark-app'

# Security & Encryption
brew 'age'
brew 'git-filter-repo'
brew 'gitleaks'
brew 'sops'
brew 'trivy'
cask 'gpg-suite'

###########################################################
# Desktop Apps                                            #
###########################################################

# Productivity
cask '1password' if COMPUTER_NAME == 'fmurodov-pro'
cask 'raycast', args: { require_sha: false }

# Communication
cask 'discord'
cask 'slack' if COMPUTER_NAME == 'fmurodov-pro'
cask 'telegram'
cask 'whatsapp'
cask 'zoom'

# Browsers
cask 'comet'
cask 'firefox'
cask 'google-chrome'

# Utilities
cask 'balenaetcher'
cask 'keka'
cask 'mac-mouse-fix'
cask 'monitorcontrol'
cask 'raspberry-pi-imager'
mas 'Discovery - DNS-SD Browser', id: 1381004916
mas 'Itsyhome', id: 6758070650
mas 'PDFScanner', id: 410968114

# Creative
cask 'bambu-studio'
cask 'orcaslicer'

###########################################################
# VS Code Extensions                                     #
###########################################################

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

# Languages
vscode 'golang.go'
vscode 'ms-python.python'
vscode 'ms-vscode.cmake-tools'
vscode 'ms-vscode.cpptools'
vscode 'ms-vscode.cpptools-extension-pack'
vscode 'ms-vscode.cpptools-themes'
vscode 'ms-vscode.makefile-tools'
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
vscode 'quicktype.quicktype'
vscode 'redhat.vscode-yaml'
vscode 'zainchen.json'

# Documentation
vscode 'bierner.markdown-mermaid'
vscode 'davidanson.vscode-markdownlint'

# Embedded & Virtualization
vscode 'bbenoist.vagrant'
vscode 'espressif.esp-idf-extension'
vscode 'marcostazi.vs-code-vagrantfile'

# Utilities
vscode 'aaron-bond.better-comments'
vscode 'adamhartford.vscode-base64'
vscode 'ibm.output-colorizer'
vscode 'kamikillerto.vscode-colorize'
vscode 'keesschollaart.vscode-home-assistant'
vscode 'moshfeu.compare-folders'
vscode 'ms-vscode.hexeditor'
vscode 'tatsy.vscode-3d-preview'
