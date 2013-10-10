To install this environment on your machine do the following:
* Check out this package to $HOME/.env/Env
* ZSH
    * Ensure you are using the zsh shell. Use chsh if needed to change to the zsh shell
    * Create ~/.zshenv and edit it
        * Set the path to this package with export ZSH_ENV="$HOME/.env/Env"
    * Create ~/.zshrc and edit it
        * Run the example zshrc by adding the following line source /home/dlouw/.env/Env/zsh/zshrc.example
        * Edit your ~/.zshrc to include whichever scripts you want
* Scripts
    * Create a ~/bin directory and symbolic whichever Env/bin scripts you want there.  If you want all of them then just add the path to Env/bin to the front of your path
* VIM
    * Symbolic link Env/vim to ~/.vim
    * Symbolic link ~/.vim/vimrc to ~/.vimrc
* Git
    * Edit your .gitconfig file in your home directory.  Add a [include] section and add an entry in that section that is path = .env/Env/git/.gitconfig
