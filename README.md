A dark minimal vim theme with a touch of hot pink and cyan. Fork of [noirblaze-vim](https://github.com/n1ghtmare/noirblaze-vim).

![antheme](https://github.com/jurelik/vim-antheme/assets/43504530/eef691d7-8e17-4661-beb9-af7e3a003bfb)

## Installation

If you're using vim-plug you can add the following to your plugin call:

```vim
Plug 'jurelik/vim-antheme'
```

Or if you're using [packer.nvim](https://github.com/wbthomason/packer.nvim):

```lua
use "jurelik/vim-antheme"
```

Then in your config add (for vim):

```vim
syntax enable
colorscheme antheme
```

Or, for neovim with `lua`:

```lua
vim.opt.background = "dark"
vim.cmd("colorscheme antheme")
```

You can also enable the lightline theme by including the following:

```vim
let g:lightline = { 'colorscheme': 'antheme' }
```
