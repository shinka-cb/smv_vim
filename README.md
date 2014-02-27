Vim setting files for SMV
=========================

Note that this vim setting files for SMV is originally from [NuSMV WebSite](http://www.cs.cmu.edu/~modelcheck/smv/vimrc).

The purpose of this repository is to make easier to introduce SMV settings using tools such as Vundle, NeoBundle and so on.

### Credits
- Armin Biere (The file `syntax/smv.vim` is the very thing that he contribute)
- SHiNKA(@shinka_cb) (Repository Maintainer)

### Installation
- Using [NeoBundle](https://github.com/Shougo/neobundle.vim),
  add this line to your `.vimrc`

```vim
NeoBundleLazy 'shinka-cb/smv_vim', {'autoload':{'filetypes':['smv']}}
```

- Using [Vundle](https://github.com/gmarik/vundle),
  add this line to your `.vimrc`

```vim
Bundle 'shinka-cb/smv_vim'
```

### License
The same as original smv.vim
