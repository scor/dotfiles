Useful bash routines for developing with git on mac os. Includes Git completion
and Git-aware PS1.

Based on [Git completion](https://github.com/git/git/blob/master/contrib/completion/git-completion.bash) with input from [msonnabaum](http://twitter.com/#!/msonnabaum).

See [screenshot of Git-aware PS1 in action](https://skitch.com/scor/gffbu/git-completion).

Installation
------------

1. Add this line at the bottom of your local .bash_profile, .profile or .bashrc:

    ```
    . "$HOME/dotfiles/.profile"
    ```
    
1. If you don't already have a .gitconfig in your HOME directory, copy dotfiles/.gitconfig into your home directory and tweak the username and email address.
If you already have your own .gitconfig, choose the lines you like from dotfiles/.gitconfig and add them to your .gitconfig
