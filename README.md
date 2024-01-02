# ansible_pull_console

## Preconditions
Debian based distro with git and ansible installed
```bash
sudo apt install git ansible
```
## Usage
```bash
sudo ansible-pull -U https://github.com/syndagate/ansible_pull_console.git -C master
```
## Description
This installs the terminal emulator 'qterminal' with matching color scheme. In addition, zsh will be installed with the following extensions:
* https://github.com/zsh-users/zsh-history-substring-search.git
* https://github.com/zsh-users/zsh-syntax-highlighting.git
* https://github.com/zsh-users/zsh-autosuggestions.git
* https://github.com/zsh-users/zsh-completions.git
* https://github.com/olivierverdier/zsh-git-prompt.git

Feel free to fork this repo and adjust it to your needs. Above all, the users in the 'host_vars/localhost.yml' file should be adapted to your needs.
## Screenshots
![](example01.png?raw=true)  

![](example02.png?raw=true)
