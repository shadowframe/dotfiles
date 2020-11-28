# dotfiles
my dotfiles vim and all the other stuff

![screenshot with vim, visualstudio code, filebrowser and terminal](readme.png)

## Gnome Tweaks

### Minimize to Dock
`gsettings set org.gnome.shell.extensions.dash-to-dock click-action 'minimize'`

### .icons
Gruvbox-Material-Dark

### .themes
Gruvbox-Material-Dark

## .vimrc
`curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim`

`:source %`

`:PlugInstall`

## Terminal beauty
`sudo apt-get install dconf-cli uuid-runtime`

`ash -c  "$(wget -qO- https://git.io/vQgMr)"`

select Gruvbox

## Visual Studio Code

Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

`ext install jdinhlife.gruvbox`
