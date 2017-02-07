# shawn-vim

## Installtion

### 1. Backup your original vim files

```
mv ~/.vimrc ~/.vimrc_backup
mv ~/.vim ~/.vim_backup
```

### 2. Check out from github

```
git clone https://github.com/seasonstar/shawn-vim.git ~/.vim
```

### 3. Link ~/.vimrc

```
ln -s ~/.vim/vimrc ~/.vimrc
```

## Keyboard shortcuts

**Please keep your mind that `<leader>` is set to `,`**

* `<F7>` Toggle NERDTreeFind
* `<F8>` Toggle NERDTree
* `<F9>` Toggle TagList
* `<F10>` Toggle paste mode
* `<leader><leader>` Trig EasyMotion (e.g. `<leader><leader>w` `<leader><leader>f` etc.)
* `<leader>s` Horizontally split window
* `<leader>v` Vertically split window
* `Ctrl-[hjkl]` Move between windows (left down up right)
* `<leader>V` Reselect the text that was just pasted
* `<leader>w` Strip all trailing whitespace in the current file
* `<leader>lc` Toggle highlight cursor column
* `<leader>ll` Toggle highlight cursor line
* `<leader>ms` Display 80-column indication
* `<leader>mh` Hide 80-column indication
* `<leader>be` Toggle BufExplorer
* `<leader>c<space>` Toggle NERDCommenter
* `<leader>ig` Toggle indent guides
