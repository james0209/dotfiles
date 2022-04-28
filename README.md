# 📄Dotfiles

## Usage / Installation

### Deploy configs

```bash
git clone https://github.com/james0209/dotfiles.git ~/.dotfiles
cd ~/.dotfiles
./install
```

This will clone all dotfiles and create symlinks to their according place, powered by
[dotbot](https://github.com/anishathalye/dotbot)

### Shell Autocompletion

Includes autocompletion from [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)

```bash
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

zshrc config already includes:

```bash
plugins=(zsh-autosuggestions)
```
