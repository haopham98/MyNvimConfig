## Install Vimplug Neovim
*https://github.com/junegunn/vim-plug*
##### Linux:
Open terminal and run command:
 `sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim' `

##### Windows:
Run on Powershell
`iwr -useb https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim |
    ni "$(@($env:XDG_DATA_HOME, $env:LOCALAPPDATA)[$null -eq $env:XDG_DATA_HOME])/nvim-data/site/autoload/plug.vim" -Force`

## Install required package
- Windows: 
	+ `$ pip install pynvim`
	+ `$ choco install universal-ctags`
- Linux:  
	+ `$ sudo apt install ctags`
	+ `$ pip3 install pynvim`
## Move to Nvim Home Directory and install
- Windows: ~/AppData/Local/
- Linux: ~/.config/
Git clone and rename this repository to <nvim>

## [Note]
- Can run on both Window and Linux
- Run command :checkhealth to check your system
- Run command :PlugInstall after pulling this resource

## [Requirement]
- NerdFont (*https://www.nerdfonts.com/*)
- NodeJS
- Python
- Git
- vim-plug
- bat
