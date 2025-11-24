# 🌵 desert256Ext

An extended version of the classic **desert256** colorscheme for Vim/Neovim — now with **three variants**:

- **normal** → balanced classic desert look  
- **dark** → reduced brightness & softer contrast  
- **darker** → deep grayscale for low-light coding sessions  

Preserves desert256’s warmth while ensuring better comfort on modern dark terminals.

---

## 🚀 Features

✔ Three selectable darkness levels  
✔ Truecolor support (with 256-color fallback)  
✔ Works in Vim and Neovim  
✔ Clean contrast and readable syntax highlighting  
✔ Easy customization for power users  

---

## 📦 Installation

### Using Vim-Plug

Add this to your `~/.vimrc` or `init.vim`:

```vim
<<<<<<< HEAD
<<<<<<< HEAD
Plug 'aroCODE99/desert256Ext'

```Set the variant before loading the theme:

" Options: normal | dark | darker
let g:desert_variant = "darker"
colorscheme desert256Ext

If you do not set g:desert_variant:
🟩 Default: normal
