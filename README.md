# wolfram-vim
Wolfram Language syntax coloring file for Vim

Installation:

```
git clone git@github.com:arnoudbuzing/wolfram-vim.git
```

(Or via https: `git clone https://github.com/arnoudbuzing/wolfram-vim.git`)

and then copy `syntax/wl.vim` to `~/.vim/syntax/wl.vim` (or `$HOME/vimfiles/syntax/wl.vim` on Windows)

Enable in Vim

```
set syntax=wl
```

Enable automatically when Vim is started, add the following to `~/.vimrc`:

```
autocmd BufNewFile,BufRead *.wl set syntax=wl
autocmd BufNewFile,BufRead *.wls set syntax=wl
autocmd BufNewFile,BufRead *.m set syntax=wl
```
