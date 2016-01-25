The Installation in HOME-USER-FOLDER execute follow terminal commands:

    git clone https://github.com/svenmauer/dotvim.git ~/.vim
    git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle
    cp ~/.vim/.vimrc ~/

    Install bundles with Vundler in VIM: `BundleInstall!
    
    ON UBUNTU x64
    Install development tools and CMake: sudo apt-get install build-essential cmake

    Make sure you have Python headers installed: sudo apt-get install python-dev

    Compiling YCM with semantic support for C-family languages:

    cd ~/.vim/bundle/YouCompleteMe
    ./install.py --clang-completer
    
    vim ~/.bashrc
    alias tmux="TERM=screen-256color-bce tmux"
    
    And set up the default-terminal option in ~/.tmux.conf:

    set -g default-terminal "xterm"
    Lastly, do $ source ~/.bashrc to load new alias.

The unmodificated files source: https://github.com/hojberg/dotvim
