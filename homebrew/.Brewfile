# ==============================================================================
#  Brewfile —— 本机 Homebrew 软件清单快照
#  生成时间：2026-10-01     主机：Zoe 的 Mac (Apple Silicon / macOS 27)
#  生成命令：brew bundle dump --file=~/.Brewfile --force --formula --cask --tap --vscode
# ==============================================================================
#
#  【新设备一条命令恢复】
#    1) 先装 Homebrew（新机器上跑官方脚本）：
#       /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
#    2) 把本文件原样拷到新机器的 ~/.Brewfile（或直接 clone 你的 dotfiles 仓库）
#    3) 恢复全部软件：
#       brew bundle install --global          # 文件名是 ~/.Brewfile，--global 会自动找到
#       # 等价写法：brew bundle install --file=~/Brewfile
#
#  【日常配套命令】
#       brew bundle check   --global          # 体检：还缺哪些没装
#       brew bundle cleanup --global          # 列出"多装"的（不加 --force 只列出，不会删）
#       brew bundle dump    --global --force --formula --cask --tap --vscode   # 重新打快照
#
#  【注意事项】
#   · brew bundle 自 Homebrew 4.5.0（2025-04-29）起已是**内置命令**，
#     homebrew/bundle 这个 tap 已被官方归档清空（2025-03 / 2025-04），
#     所以：无需 tap 它，无需 untap，`brew bundle` 一切照旧可用。
#   · Homebrew 6.0.22 的 dump 默认只导出 vscode 扩展，必须显式加
#     --formula --cask --tap 才会导出命令行工具与 GUI 应用，切记。
#   · 建议把本文件纳入 dotfiles / 私有 Git 仓库，换机时 clone 即可。
#   · macOS 的 .app 里若含「App Store」购买的软件，本文件无法覆盖，
#     需另装 mas（brew install mas）后用 mas list / mas install 处理。
#
# ------------------------------------------------------------------------------
#  Taps（第三方仓库）
# ------------------------------------------------------------------------------
tap "farion1231/ccswitch"        # cc-switch 的来源；Homebrew 6 起非官方 tap 默认不受信任
tap "localsend/localsend"        # localsend 的来源；恢复后可能需要：brew trust <tap>
# tap "homebrew/cask-fonts"      # 【已废弃】字体 cask 已全部合并进 homebrew/cask，无需再 tap

# ------------------------------------------------------------------------------
#  Formulae（命令行工具 / 库，共 21 个）
# ------------------------------------------------------------------------------
# ⚠️ 已弃用/停更项：openssl@1.1、libassuan@2 —— 建议换 openssl@3、libassuan
# Automatic configure script builder
brew "autoconf"
# Cryptography and SSL/TLS Toolkit
brew "openssl@3", link: true
# Shell extension to jump to frequently used directories
brew "autojump"
# Tool for generating GNU Standards-compliant Makefiles
brew "automake"
# Dependency manager for Cocoa projects
brew "cocoapods"
# GNU File, Shell, and Text utilities
brew "coreutils"
# Distributed revision control system
brew "git"
# Assuan IPC Library
brew "libassuan@2"
# X.509 and CMS library
brew "libksba"
# Generic library support script
brew "libtool"
# Utility for directing compilation
brew "make"
# Open-source, cross-platform JavaScript runtime environment
brew "node"
# Cryptography and SSL/TLS Toolkit
brew "openssl@1.1"
# Pinentry for GPG on Mac
brew "pinentry-mac"
# Package compiler and linker metadata toolkit
brew "pkgconf"
# Fast, disk space efficient package manager
brew "pnpm"
# Extremely fast Python package installer and resolver, written in Rust
brew "uv"
# Internet file retriever
brew "wget"
# General-purpose lossless data-compression library
brew "zlib"
# Fish-like fast/unobtrusive autosuggestions for zsh
brew "zsh-autosuggestions"
# Additional completion definitions for zsh
brew "zsh-completions"

# ------------------------------------------------------------------------------
#  Casks（GUI 应用，共 27 个）
# ------------------------------------------------------------------------------
# ⚠️ codex-app 已被官方弃用/禁用，恢复时可能失败，注意找替代品
# Android SDK component
cask "android-platform-tools"
# User-friendly GUI app for Homebrew
cask "applite"
# Configuration manager for AI coding agents
cask "cc-switch"
# Desktop client that supports multiple LLM providers
cask "cherry-studio"
# OpenAI's Codex desktop app for managing coding agents
cask "codex-app"
# App to build and share containerised applications and microservices
cask "docker-desktop"
# Project management software
cask "feishu"
# Fonts
cask "font-google-sans"
cask "font-google-sans-code"
cask "font-sauce-code-pro-nerd-font"
# Terminal emulator that uses platform-native UI and GPU acceleration
cask "ghostty"
# Xcode extension for GitHub Copilot
cask "github-copilot-for-xcode"
# Web browser
cask "google-chrome"
# Utility to hide menu bar items
cask "hiddenbar"
# Homebrew's official GUI
cask "homebrew-app"
# Free cross-platform office suite, fresh version
cask "libreoffice"
cask "localsend"
# Multi-platform web browser
cask "microsoft-edge"
# App to write, plan, collaborate, and get organised
cask "notion"
# Utility to uninstall apps and remove leftover files from old/uninstalled apps
cask "pearcleaner"
# System monitor for the menu bar
cask "stats"
# Tencent Git GUI Client
cask "tencent-ugit"
# Adaptive AI IDE
cask "trae-cn"
# Open-source code editor
cask "visual-studio-code"
# Manage Homebrew packages with a UI
cask "wailbrew"
# Rust-based terminal
cask "warp"
# AI agent for everyday office work
cask "workbuddy-cn"

# ------------------------------------------------------------------------------
#  VS Code 扩展（共 63 个，由 brew bundle 通过 `code --install-extension` 恢复）
#  前置条件：已装 visual-studio-code（见上面 cask）且 code 命令已加入 PATH
# ------------------------------------------------------------------------------
vscode "aaron-bond.better-comments"
vscode "adpyke.codesnap"
vscode "alefragnani.bookmarks"
vscode "anthropic.claude-code"
vscode "blackmery.vscode-switcher"
vscode "catppuccin.catppuccin-vsc"
vscode "christian-kohler.path-intellisense"
vscode "cschlosser.doxdocgen"
vscode "dart-code.dart-code"
vscode "davidanson.vscode-markdownlint"
vscode "donjayamanne.githistory"
vscode "eamodio.gitlens"
vscode "formulahendry.code-runner"
vscode "golang.go"
vscode "guodongsun.vscode-git-cruise"
vscode "intellsmi.comment-translate"
vscode "ionutvmi.path-autocomplete"
vscode "james-yu.latex-workshop"
vscode "jeff-hykin.better-cpp-syntax"
vscode "jock.svg"
vscode "lihuiwang.vue-alias-skip"
vscode "llvm-vs-code-extensions.lldb-dap"
vscode "mechatroner.rainbow-csv"
vscode "mhutchie.git-graph"
vscode "mitaki28.vscode-clang"
vscode "ms-azuretools.vscode-containers"
vscode "ms-ceintl.vscode-language-pack-zh-hans"
vscode "ms-python.debugpy"
vscode "ms-python.python"
vscode "ms-python.vscode-pylance"
vscode "ms-python.vscode-python-envs"
vscode "ms-vscode-remote.remote-containers"
vscode "ms-vscode-remote.remote-ssh"
vscode "ms-vscode-remote.remote-ssh-edit"
vscode "ms-vscode-remote.remote-wsl"
vscode "ms-vscode-remote.vscode-remote-extensionpack"
vscode "ms-vscode.cmake-tools"
vscode "ms-vscode.cpp-devtools"
vscode "ms-vscode.cpptools"
vscode "ms-vscode.cpptools-extension-pack"
vscode "ms-vscode.cpptools-themes"
vscode "ms-vscode.powershell"
vscode "ms-vscode.remote-explorer"
vscode "ms-vscode.remote-server"
vscode "naumovs.color-highlight"
vscode "obkoro1.korofileheader"
vscode "openai.chatgpt"
vscode "openai.codex-audio"
vscode "pkief.material-icon-theme"
vscode "remisa.shellman"
vscode "steoates.autoimport"
vscode "streetsidesoftware.code-spell-checker"
vscode "sweetpad.sweetpad"
vscode "swiftlang.swift-vscode"
vscode "tomoki1207.pdf"
vscode "twxs.cmake"
vscode "vadimcn.vscode-lldb"
vscode "vincaslt.highlight-matching-tag"
vscode "vintharas.learn-vim"
vscode "vscode-icons-team.vscode-icons"
vscode "w88975.code-translate"
vscode "wix.vscode-import-cost"
vscode "yzhang.markdown-all-in-one"

# ==============================================================================
#  以下不属于 Homebrew，Brewfile 管不到，换机时请单独处理
# ==============================================================================
#
# 【npm 全局包】恢复命令（需先有 node/npm）：
#   npm i -g @anthropic-ai/claude-code @openai/codex @deepseek-ai/dsh \
#            @larksuite/cli meitu-designkit-cli mineru-open-api
#
# 【uv 工具】本机当前无（uv tool list 为空），将来装了可用：
#   uv tool list                                  # 备份
#   uv tool install <name>                        # 恢复
#
# 【RVM / Ruby】~/.rvm 下的 Ruby 3.1.2，换机需重装 RVM
#
# 【系统级】shell 配置（~/.zshrc、~/.p10k.zsh、~/powerlevel10k）、
#           ~/.workbuddy、~/.claude、~/.dsh 等配置目录请一并迁移或重建
# ==============================================================================
