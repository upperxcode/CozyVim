# CozyVim

<p align="center">
  <img src="https://user-images.githubusercontent.com/45173070/221726955-6126fdbb-cdac-46ef-834f-c5cc323d9b99.png" />
</p>
<p align="center">
  <img src="https://user-images.githubusercontent.com/45173070/221728266-dcaf72fe-8625-4443-a80d-04dc52cce4d2.png" />
</p>

My personal, modern and easily extendable configuration for nvim. Basically my own minimalistic take on LunarVim/LazyVim.

## Features

- Preconfigured base config for NeoVim
- Easily extendable and customizable
- Very fast lazy plugin loading using [lazy.nvim](https://github.com/folke/lazy.nvim)
- Multiple Treesitter supported Colorthemes preinstalled
- Default configs for LSP, linting, formatting, autocompletions, integrated terminals and more

## Requirements

- Neovim >= 0.8.0
- `git`, `make`, `pip`, `python`, `npm`, `node`, `cargo`
- `lazygit` (hightly recommended)

## Getting Started

- Make a backup of your existing config (if it exists):
```bash
# required
mv ~/.config/nvim ~/.config/nvim.bak

# optional but recommended
mv ~/.local/share/nvim ~/.local/share/nvim.bak
mv ~/.local/state/nvim ~/.local/state/nvim.bak
mv ~/.cache/nvim ~/.cache/nvim.bak
```
- CozyVim can be now be installed like so:
```bash
git clone https://github.com/ingur/CozyVim ~/.config/nvim && nvim
```
> NOTE: missing dependencies/plugins are mostly installed automatically, in case something does not work immediately, you might need to restart Neovim

- Be sure to run `:checkhealth` whenever you get stuck
- If you ever run into other errors, you can always reset CozyVim like so:
```bash
rm -rf ~/.local/share/nvim ~/.local/state/nvim/lazy ~/.config/nvim/lua/custom/lazy-lock.json
```

## TODO
- Documentation
