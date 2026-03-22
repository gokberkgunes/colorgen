Lua based Color scheme generator for neovim

## Requirements
```sh
PyYAML==5.4.1
```
## Generate your colorscheme
```sh
python ez.py theme.yml
```

## After generating your colorscheme the following configuration options should be available
```lua
vim.g.transparent_background = true        -- transparent background(Default: false)
vim.g.italic_comments = true               -- italic comments(Default: true)
vim.g.italic_keywords = true               -- italic keywords(Default: true)
vim.g.italic_functions = true              -- italic functions(Default: false)
vim.g.italic_variables = true              -- italic variables(Default: false)
```

## Put the files directly too lua folder in neovim, if you're importing as folder change init.lua
```lua
local util = require("core.neptunus.util")
```

Original script is from: [ez.nvim](https://github.com/Murtaza-Udaipurwala/ez.nvim)
