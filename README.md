# my-config

Personal dotfiles & config backup. Mostly for my own use, but feel free to reference or steal anything useful.

## Contents

- `nvim/` — Neovim config (Lua-based, using lazy.nvim)
- `starship.toml` — Starship prompt config
- `.zshrc` — Zsh shell config
- `config.ghostty` — Ghostty terminal config

---

## Neovim

Lua-based config using [lazy.nvim](https://github.com/folke/lazy.nvim) as the plugin manager.

**Structure:**
```
nvim/
├── init.lua
├── lazy-lock.json
└── lua/
```
---

## CLI Tools

### Starship
Fast, cross-shell prompt with endless customization.
- Install: https://starship.rs
- Config: copy `starship.toml` to `~/.config/starship.toml`

### rxfetch
Minimal system info fetcher for the terminal.
- Install: https://github.com/Mangeshrex/rxfetch

---

## Usage

Clone the repo and symlink or copy whichever config you need.

```bash
git clone https://github.com/sayidil-anam/my-config
```
