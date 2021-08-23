# Git config for windows

* save git-completion.bash in home directory
* save git-prompt.sh in home directory
* save bash_profile in home directory and rename to .bash_profile

## Git configurations

```
git config --global core.editor "'C:/Program Files/Sublime Text/sublime_text.exe' -n -w"
git config --global push.default upstream
git config --global merge.conflictstyle diff3
```

## To make sublime default editor

`alias subl="C:/Program\ Files/Sublime\ Text/sublime_text.exe"`

## restart git bash to take effect