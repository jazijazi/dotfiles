# dotfiles

### how add on local
```
1. mkdir $HOME/dotfiles
2. git init --bare $HOME/dotfiles
3. echo 'alias dotfilecfg="/usr/bin/git --git-dir=$HOME/dotfiles --work-tree=$HOME" ' >> $HOME/.zshrc
4. dotfilecfg config --local status.showUntrackedFiles no
5. dotfilecfg remote add origin ---git repo address---
6. dotfilecfg branch -M main
7. dotfilecfg add $HOME/.zshrc
8. dotfilecfg push -u origin main
```
