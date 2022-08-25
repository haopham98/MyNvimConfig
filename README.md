# Install Vimplug Neovim
https://github.com/junegunn/vim-plug
- Linux:
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'

- Windows:
iwr -useb https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim |`
    ni "$(@($env:XDG_DATA_HOME, $env:LOCALAPPDATA)[$null -eq $env:XDG_DATA_HOME])/nvim-data/site/autoload/plug.vim" -Force

[Note]
- Can run on both Window and Linux
- Run command :checkhealth to check your system
- Run command :PlugInstall after pulling this resource

[Requirement]
- NodeJS
- Python
- Git
- vim-plug
- bat
