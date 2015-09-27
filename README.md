# simple_bash_prompt

A simple bash prompt for ruby and RVM users. Features colors and shows current folder, ruby version, gemset, and git branch.

![sexy-bash-prompt screenshot][screenshot]

[screenshot]: screenshot.png

## Install
Just copy and paste this line in your terminal:

```bash
(cd $HOME && wget https://raw.githubusercontent.com/dkoloditch/simple_bash_prompt/master/.bash_prompt) && (echo "" >> $HOME/.bashrc && echo "source $HOME/.bash_prompt" >> $HOME/.bashrc) && source $HOME/.bashrc
```

## Uninstall
1. ```rm $HOME/.bash_prompt```
2. Open $HOME/.bashrc and remove the line "source $HOME/.bash_prompt"

Enjoy.
