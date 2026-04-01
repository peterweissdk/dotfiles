# 🚀 My Terminal Setup Checklist

### 1. ZSH & Oh My Zsh
- [ ] Install ZSH: `sudo apt install zsh`
- [ ] Install Oh My ZSH: `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`

### 2. Starship Prompt
- [ ] Install: `curl -sS https://starship.rs/install.sh | sh -s -- -y`
- [ ] Check for updates: `starship --version`

### 3. Plugins
Run these to clone missing plugins:
- [ ] `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting`
- [ ] `git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions`
- [ ] `git clone https://github.com/zsh-users/zsh-history-substring-search ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-history-substring-search`

### 4. Fonts
- [ ] Install **JetBrainsMono Nerd Font** (Required for icons!)
