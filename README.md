# Start

1. Create a suitable name for the new kit in network sharing settings
2. Enable file vault encryption
3. Generate new a ssh key pair `ssh-keygen -t rsa`

# Git

Change default editor to nano 
```
git config --global core.editor "nano"
```

# Terminal

Install iTerm: https://www.iterm2.com

Change default shell to zsh 
```
chsh -s /bin/zsh
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


# VSCode settings
```
{
    "editor.formatOnPaste": true,
    "workbench.colorTheme": "Nord",
    "editor.fontSize": 12,
    "editor.minimap.enabled": false,
    "workbench.startupEditor": "newUntitledFile",

    "files.exclude": {
        "**/.git": true,
        "**/.svn": true,
        "**/.hg": true,
        "**/CVS": true,
        "**/.DS_Store": true,
        "**/.yarn-cache": true,
        "**/.eggs": true,
        "**/.cache-loader": true
    },
    "files.insertFinalNewline": true,
    "search.exclude": {
        "**/node_modules/**": true,
        "**/bower_components/**": true,
        "**/dist/**": true
    },
    "files.watcherExclude": {
        "**/.git/objects/**": true,
        "**/.git/subtree-cache/**": true,
        "**/node_modules/**": true,
        "**/.yarn-cache": true,
        "**/.eggs": true,
        "**/.cache-loader": true
    },
    "explorer.confirmDragAndDrop": false,
    "eslint.autoFixOnSave": true,
    "[scss]": {
        "editor.tabSize": 2
    },
    "terminal.integrated.fontFamily" : "Roboto Mono Light for Powerline"
}
```
