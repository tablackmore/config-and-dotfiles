# config-and-dotfiles
My computer config for terminal git and node on new machine

1) Switch to zsh and install prezto following this guide:

https://github.com/sorin-ionescu/prezto

2) Download and install the powerline fonts
https://github.com/powerline/fonts

3) Install iterm2
https://www.iterm2.com/

4) Open iterm2 and replace the .zpreztorc and .zshrc with the ones in this directory.

5) Open preferences in iterm2 and profile -> text change non-ascii font to 12pt Meslo LG S Regular for Powerline (Font installed at step 2)

6) Setup node to install globals without -g
curl https://raw.githubusercontent.com/glenpike/npm-g_nosudo/master/npm-g-nosudo.sh | sh