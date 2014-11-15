vim-rusth
=========

Small script based on [uzbl](http://uzbl.org/) for viewing online rust docs
from Vim.

# Installation #

The binary can be placed anywhere visible to Vim. I recommend a standard binary
path like `/usr/local/bin`.

Set 'keywordprg' to the rusth script. This is only helpful for Rust buffers, so
if you have autocmd and
(rust.vim)[https://github.com/scott-linder/vim-rusth.git] you can add something
like the following to your vimrc:
```
au FileType rust setl keywordprg=/usr/local/bin/rusth
```

# Usage #

See the Vim `:help K`
