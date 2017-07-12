# My vim setup

Simple vim setup.  

### Install prerequisite

First, let's make a directory to house all vim config files 
```bash 
mkdir ~/.vim; cd ~/vim
```

Next, let's clone all relevant git repos.

```bash 
git clone https://github.com/watsonryan/vimSetup.git
git clone https://github.com/tpope/vim-pathogen.git
git clone https://github.com/flazz/vim-colorschemes.git
```

Now, lets start setting up vim.

```bash
mv vimSetup/vimrc ~/.vimrc; mv vimSetup/Xmodmap ~/.Xmodmap;
mkdir -p ~/.vim/autoload ~/.vim/bundle
cp vim-pathogen/autoload/pathogen.vim autoload
cd vim-colorschemes
git submodule add https://github.com/flazz/vim-colorschemes.git bundle/colorschemes
mkdir colors; cp -R vim-colorschemes/bundle/colorschemes/colors/* colors
```
Hopefully it works. 
