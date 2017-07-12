# My vim setup

### Install prerequisite

```bash
mkdir ~/.vim; cd ~/vim
git clone
mv vimrc ~/.vimrc; mv Xmodmap ~/.Xmodmap;
git clone https://github.com/tpope/vim-pathogen.git
mkdir -p ~/.vim/autoload ~/.vim/bundle
cp vim-pathogen/autoload/pathogen.vim autoload
git clone https://github.com/flazz/vim-colorschemes.git
cd vim-colorschemes
git submodule add https://github.com/flazz/vim-colorschemes.git bundle/colorschemes

