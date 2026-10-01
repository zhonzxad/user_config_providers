# 备份命令
brew bundle dump --file=~/.Brewfile --force --formula --cask --tap --vscode
# 新设备恢复
# 1) 装 Homebrew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# 2) 把 .Brewfile 放到新机器 ~/ 下（或直接 clone dotfiles 仓库）

# 3) 一键装回全部
brew bundle install --global
