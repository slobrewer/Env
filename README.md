To install this environment on your machine do the following:
* ZSH
    * Ensure you are using the zsh shell
    * Copy Env/zsh/zshrc.example to ~/.zshrc and edit it
        * Ensure ZSH_ENV points to the full path to this Git package
            * You can do this by setting ZSH_ENV in your .zshenv file
        * Edit your ~/.zshrc to include whichever scripts you want
    * Symbolic link Env/zsh to ~/.zsh
* Scripts
    * Create a ~/bin directory and symbolic whichever Env/bin scripts you want there.  If you want all of them then just add the path to Env/bin to the front of your path
* VIM
    * Symbolic link Env/vim to ~/.vim
    * Symbolic link ~/.vim/vimrc to ~/.vimrc
