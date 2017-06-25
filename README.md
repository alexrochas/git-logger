# Git Logger
> An minimal git wrapper to capture local git usage

This project comes from the idea to write and help other with some git/github knowledgement. For that my thought was, if I knew the most commom errors on git usage, I would be able to help.

The scripts above don't capture anything more that how you use git. It will not capture passwords and stuff. Unless you for some reason write it as a git commit message. Hope not!

## Install

First copy the git-logger file to your home and rename it.
```shell
~/[path_to_project]$ cp ./git-logger ~/.git-logger
```
This will keep the git-logger file out of your way.

Second, guarantee that has execution permissions.
```shell
~$ chmod +x ./.git-logger
```

Finally, in your terminal emulator config file (bashrc, zshrc, fishrc) create an alias overriding git:
```vim
alias git='~/.git-logger'
```

## Development

In order to test the autocomplete (currently only for zsh):

```shell
 ~/git-logger$ source ./git-logger.plugin.zsh
 ~/git-logger$ rm -f ~/.zcompdump; compinit
```

## Roadmap

* ~~Send usage to git-logger-api~~
* ~~Create how-to install~~
* Create how to install autocomplete

## Release History

* 0.0.1
    * Work in progress

## Meta

Alex Rocha - [about.me](http://about.me/alex.rochas)
