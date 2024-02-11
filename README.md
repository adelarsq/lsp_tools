# lsp_tools

> Note: It's easier to use autocmds on current Neovim nightly than before. So there is no need for this plugin anymore. Archiving for reasearch pourpouses only.

Provide some tools for a better Neovim experience with LSP.

# Features

- [x] codelens
- [x] document highlight

## Installing

Install with you favorite plugin manager then on the on_attach method call:

```lua
require('lsp_tools').on_attach(client, bufnr)
```

## Credits

- [VidocqH/lsp-lens.nvim](https://github.com/VidocqH/lsp-lens.nvim)
- [chikko80/error-lens.nvim](https://github.com/chikko80/error-lens.nvim)
- [lvimuser/lsp-inlayhints.nvim](https://github.com/lvimuser/lsp-inlayhints.nvim)
