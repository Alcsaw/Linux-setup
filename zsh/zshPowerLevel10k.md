# Zsh P10K
This configuration files are used to setup Z Shell with Power Level 10000 theme.

![example](./example.png)

---

Resources used:
https://github.com/zsh-users/zsh
https://github.com/romkatv/powerlevel10k
https://github.com/zsh-users/zsh-autosuggestions


## Setup steps

On Windows 10 (WSL2):

1. Install Windows Terminal
2. [Install p10k recommended font](https://github.com/romkatv/powerlevel10k#meslo-nerd-font-patched-for-powerlevel10k)
3. Setup the newly installed font in Terminal Settings ([settings.json available in this repo dir](./windowsTerminalSettings.json))
4. [Setup WSL2](https://docs.microsoft.com/en-us/windows/wsl/install-win10)
5. Install Ubuntu from MS Store

On Linux (Ubuntu 20.04):

6. Install Zsh (`sudo apt install zsh`)
7. Install [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) ([Manual installation](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#manual-git-clone))
8. Copy the contents of [zshrc](./zshrc) to your `~/.zshrc`
9.  [Install p10k](https://github.com/romkatv/powerlevel10k#manual)
10. Copy the contents of [p10k.zsh](./p10k.zsh) to your `~/.p10k.zsh`
11.