To install this environment on your machine do the following:
* Check out this package to $HOME/.env/Env
* ZSH
    * Ensure you are using the zsh shell. Use chsh if needed to change to the zsh shell
    * Create ~/.zshrc and edit it
        * Run the example zshrc by adding the following line source $HOME/.env/Env/zsh/zshrc.example
    * Enable oh-my-zsh by running the following:
        * curl -L https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh | sh
        * More info at https://github.com/robbyrussell/oh-my-zsh
        * enable plugins by editing ~/.zshrc and setting the plugins= value
            * suggested plugins=(git jump)
        * set the ZSH_THEME in ~/.zshrc to agnoster
            * follow the instructions on your local machine to install the powerline patched font.  Use the one from https://github.com/Lokaltog/powerline-fonts/tree/master/Inconsolata
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
* Git
    * Edit your .gitconfig file in your home directory.  Add a [include] section and add an entry in that section that is path = .env/Env/git/.gitconfig
    * You need to be running at least git version 1.7.10 for this to work. Otherwise copy and paste it into your .gitconfig
    * Add powerline by cloning https://github.com/Lokaltog/powerline.git to ~/.env
