# Start

1. Create a suitable name for the new kit in network sharing settings
2. Enable file vault encryption
3. Generate new a ssh key pair `ssh-keygen -t rsa`


# Terminal

Install iTerm: https://www.iterm2.com

Change default shell to zsh 
```
chsh -s zsh
```

Remove any ~/.oh-my-zsh, then install oh-my-zsh
```
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

Install powerline patched fonts
```
git clone git@github.com:powerline/fonts.git 
cd fonts
./install.sh
```
Download Nord theme colours from https://github.com/arcticicestudio/nord-iterm2 and import in iterm preferences

Set font to `12pt Roboto Mono Light for powerline`


Edit `~/.zshrc` :
```
ZSH_THEME="agnoster"
DEFAULT_USER=`whoami`
```


# VSCode

