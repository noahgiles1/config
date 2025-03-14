# Windows setup and config

### Install Windows without a microsoft account
- Get to the point it asks for login
- Shift+F10 to open CMD
- `ncpa.cpl`
- Disable network adapters
- `oobe\bypassnro`
- Computer will restard, continue install
- Select "I don't have internet" and do limited install

### Debloating
I make use of talon debloater https://github.com/ravendevteam/talon, it does a pretty good job of removing crap after a fresh install and from what I can tell at the point of writing this it isn't malware.


### Terminal
Install WSL + Distro of choice

Install a nerdfont https://www.nerdfonts.com/ \
Standard for me is MesloLGS NF Regular

I use zsh with oh-my-zsh and pk10 
for pk10
```shell
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/themes/powerlevel10k
```
Find config files under [zsh](../zsh/)