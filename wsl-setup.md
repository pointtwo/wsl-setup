# Setup WSL

## WSL - Debian based distribution like (Ubuntu)

### Update the system

Update the repositories list

`sudo apt update`

Update the system packages

`sudo apt upgrade`

Note: 

The `sudo` command allows a permitted user to execute a command as the superuser or another user.

The `apt` command is a package manager that allows to manage packages.

`update ` is a `apt` option that allows update system repositories list.

`upgrade` is a `apt` option that allows update system packages. 		

### Packages that you don't need but make your experience  better

Install recommend packages

`sudo apt install zsh bat exa tldr lolcat cowsay git npm curl wget neovim htop tree `  

| Command or package | What's                                                       |
| ------------------ | ------------------------------------------------------------ |
| zsh                | Z shell, is an extended version of the Bourne Shell (sh), with plenty of new features, and support for plugins and themes. |
| bat                | It reads data from the file and gives their content as output. |
| exa                | List directory contents.                                     |
| tldr               | Show how to use a command.                                   |
| curl               | Transfers data from or to a server                           |
| lolcat             | rainbow coloring effect for text console display             |
| wget               | Download files from the Web.                                 |
| cowsay             | Configurable speaking/thinking cow.                          |
| npm                | JavaScript and Node.js package manager.                      |
| nvim               | Neovim, a programmer's text editor based on Vim              |
| tree               | Displays the contents of the current directory in the form of a tree. |

Try:

`tldr -u` 

and then;

`tldr exa` or `tldr bat`

Install recommend zsh theme and plugins 

`bash <(curl -s https://raw.githubusercontent.com/CodelyTV/dotly/HEAD/installer)`

### Alias

Add each line to .zshrc file, open with nano `nano ~/.zshrc` and paste each line

List content with icons

`alias lix="exa --icons"`

List only directories

`alias lxd="exa --icons -d */"`

List all contend in long format

`alias lxl="exa -lah"`

List of a tree view with 3 levels

`alias lxt="exa --tree --level=3 --icons"`

# Setup VSCode for WSL

Install extension `Remote - WSL`

# Install fonts on Windows

### Install programming fonts

[Click](https://github.com/pointtwo/all-fonts/archive/refs/heads/main.zip) here to download fonts .

Unzip the compress file and install for all users.

### Don't forget to change the font in VSCode settings

`'DroidSansMono Nerd Font', 'consolas'`

#### Try on terminal

`exa --icons`







