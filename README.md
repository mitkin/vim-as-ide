# TOC

 * Git and Pip are your friends:
    * Lots of projects are stored on git and
      can be installed from there directly
    * Pip allows you to get python modules that 
      are not in OS repos
    * `sudo apt-get install git python-pip`
 * Shell/CLI is your friend: your options 
    are way bigger than compared to one single
    application; terminal multiplexers (screen, tmux)
    add one more dimension on top of that
    It's much easier to become comfortable on a remote system
 * Vim is cool
    * Multimodal approach
    * buffers and tabs
    * shortcuts
    * shell access and integration
 * Make Vim look like and IDE
    * Line numbering
    * Colorschemes
    * Window splitting
 * Vim is cooler than you think 
    * Package installation
    * dotvim
 * Vim and navigation
    * tags and tags navigation
      1. Run ctags: `ctags *py`
      2. `<Ctrl>{` - jump to a class/method/function
      3. `<Ctrl>T` - jump backwards
    * File browsing: 
        * File tree: `NerdTree`
        * Fuzzy search: `ctrlp`
        * Fuzzy function search: `ctrlp-funky`
 * Vim and debugging
    * Debugging from within vim: `vim-pyclewn`
    * Call debugger from vim: `:!python -m pdb %`
 * Vim and tests
 * Vim and git 


# vim plugins
 * pathogen
 * tagbar
 * ctrlp.vim
 * ctrlp-funky
 * vim-flake8
 * vim-airline
 * vim-pyunit
 * tCommenter
 * NERDTree
 * jedi-vim
 

# Dependencies
    sudo pip install flake8
    sudo pip install git+git://github.com/nvie/nose-machineout.git#egg=nose_machineout
    sudo pip install jedi
    sudo pip install vim_bridge
    sudo apt-get install exuberant-ctags


# Links
 * http://mirnazim.org/writings/vim-plugins-i-use/
 * My dotfiles: https://github.com/mitkin/dotfiles.git
