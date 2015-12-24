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

The unmodificated files source: https://github.com/hojberg/dotvim
