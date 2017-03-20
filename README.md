# Terminal

Install iTerm: https://www.iterm2.com

Change shell to zsh 
```
chsh -s zsh
```

Install oh-my-zsh (remove any ~/.oh-my-zsh created by `mackup restore`)
```
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
Note: remove any ~/.oh-my-zsh created by `mackup restore`

Install powerline patched fonts
```
git clone git@github.com:powerline/fonts.git 
cd fonts
./install.sh
```

Download iTerm colour schemes from http://iterm2colorschemes.com
In iTerm, CMD+i -> Colors -> [select :: import]
(Spacegrey Eighties Dull)


Edit `~/.zshrc` :
```
ZSH_THEME="agnoster"
DEFAULT_USER=`whoami`
```


# Atom
```
apm install nord-atom-ui nord-atom-syntax language-babel language-elixir language-jsx autocomplete-paths linter linter-eslint linter-flake8 merge-conflicts atom-beautify pigments docblockr
```
