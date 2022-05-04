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

## Packages

- bauh
- qemu
- timeshift
- ulauncher

## Addons/Extensions

- [Bypass Paywalls](https://github.com/iamadamdev/bypass-paywalls-chrome)
- [Tiling Assistant](https://github.com/Leleat/Tiling-Assistant)
- [Gnome Fuzzy Search](https://gitlab.com/Czarlie/gnome-fuzzy-app-search)
- [Nordic Theme](https://www.gnome-look.org/p/1267246/)
- [Workspace Indicator](https://extensions.gnome.org/extension/3968/improved-workspace-indicator/)
