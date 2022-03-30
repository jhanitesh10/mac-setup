# Mac environment setup

This repository helps get a new Max OS X machine up and ready
Any existing apps must be embraced as is with warnings if there is any incompatibility.

## Entry points

1: Setu a SSH key to your GitHub account
Follow up with [Link](https://help.github.com/en/enterprise/2.15/user/articles/checking-for-existing-ssh-keys).

2: Install homebrew
Paste that in a macOS Terminal or Linux shell prompt

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

3: Clone mac-settup repo onto your lapto(Note: It's important that the directory is in your `$HOME` folder.)

```
cd ~
git clone git@github.com:jhanitesh10/mac-setup.git
```

4: Login to AppleStore

## Setup ZSH as your shell

```
sudo dscl . -create /Users/$USER UserShell /usr/local/bin/zsh
```

### Optional

```
./setup-apps
```

Sets up the apps that are commonly used.

### VS Code

```
./setup-vscode
```

## References

Setup vscode setting json file
Follow up with [Link](https://rcrdo.com/2020/03/27/must-have-vs-code-settings-for-web-development/).
Follow up with [Link](https://vigu-madurai.medium.com/must-have-settings-in-vs-code-371814ca076a).

Setup vim setting json file
Follow up with [Link](https://www.freecodecamp.org/news/vimrc-configuration-guide-customize-your-vim-editor/).
Follow up with [Link](https://vigu-madurai.medium.com/must-have-settings-in-vs-code-371814ca076a).
