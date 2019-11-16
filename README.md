# My Cowfile
This is a repo for cowfiles created by me for [cowsay](http://en.wikipedia.org/wiki/Cowsay).

## Installation
First, download and install `cowsay`.

- OSX: `brew install cowsay`
- GNU/Linux: `sudo apt-get install cowsay`, `pacman -S cowsay`, `dnf install cowsay`, etc.

Next, you need to place the cowfiles somewhere that `cowsay` can locate them. I recommend creating a `.cowsay` folder under your home directory. Clone the contents of this repo in that folder:

    git clone https://github.com/CriusT/My-Cowfile.git ~/.cowsay

Now, add the new folder to your $COWPATH environment variable. Append this line to your shell's configuration file (.bashrc, .zshrc, .cshrc, .bash_profile).

    COWPATH="$COWPATH:$HOME/.cowsay"

