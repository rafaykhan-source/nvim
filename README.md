# My Neovim Configuration

I developed this configuration as I was watching through tjdevries's
[advent of neovim series](https://github.com/tjdevries/advent-of-nvim).

## Neovim Installation

```bash
bun i -g tree-sitter-cli
```

## LSP Setup Commands

```bash
uv tool install ruff
uv tool install ty
uv tool install rumdl

bun i -g svelte-language-server
bun i -g @tailwindcss/language-server
bun i -g vscode-langservers-extracted
bun i -g typescript typescript-language-server
bun i -g bash-language-server

cargo install --git https://github.com/Myriad-Dreamin/tinymist --locked tinymist-cli

# install typst
# install marksman
# install lua-language-server


# I still haven't figured out a good latex setup yet.
# install texlab
```

## Conform Setup Commands

```bash
uv tool install ruff
uv tool install rumdl
uv tool install codespell

bun i -g @taplo/cli
bun i -g @fsouza/prettierd
bun i -g prettier

cargo install stylua

# install shellcheck
# install typstyle

# I still haven't figured out a good latex setup yet
# cargo install tex-fmt

```

## Todo

- [x] Rename plugin file names to match plugin being handles
- [x] Consolidate colorscheme plugins into a `colorscheme.lua` file
- [x] Add GitSigns
- [x] Add BigFile
- [ ] Remove lspconfig and self-configure and add a `lsp` directory
- [ ] Add typst support
- [ ] Add Neogen for autodocstring support

When nightly becomes stable:

- [ ] Switch to pack, create packer version

- [ ] Convert Commands to Lua Functions
