# ssh-connect

Forked from [gko/ssh-connect](https://github.com/gko/ssh-connect) for use in my dotfiles.
The only changes are [this fix](https://github.com/gko/ssh-connect/issues/6#issuecomment-781914359) by [XpliSyL](https://github.com/XpliSyL) which fixes history searching and a simple rename of the main file so it works with Prezto out of the box.

### Installing with [Prezto](https://github.com/sorin-ionescu/prezto)
Clone to your desired directory
```bash
git clone --recursive https://github.com/winkwonkbitch/ssh-connect
```
Add the cloned directory to your _`$ZDOTDIR/.zpreztorc`_
```bash
zstyle ':prezto:load' pmodule-dirs path/to/cloned/directory
```
And finally load the module in _`$ZDOTDIR/.zpreztorc`_
```bash
zstyle ':prezto:load' pmodule 'ssh-connect'
```

### Installing manually
Clone to your desired directory
```bash
git clone --recursive https://github.com/winkwonkbitch/ssh-connect
```
And source the plugin in your _`.zshrc`_
```bash
source /path/to/cloned/directory/ssh-connect.plugin.zsh
```
### - 01001100
All credit goes to the original authors; [Konstantin Gorodinskiy](https://github.com/gko) for [ssh-connect](https://github.com/gko/ssh-connect) and [Listbox](https://github.com/gko/listbox), and [XpliSyL](https://github.com/XpliSyL) for their [fix](https://github.com/gko/ssh-connect/issues/6#issuecomment-781914359).

# Original README
🐙 simple ssh manager. It looks for your previous ssh sessions in `$HISTFILE` and keeps relevant the ones that you reconnect to. Supports bash and zsh.

![demo](https://raw.githubusercontent.com/gko/ssh-connect/master/demo.gif)

## Installation

### Manually
```bash
git clone --recursive https://github.com/gko/ssh-connect
```
then in .bashrc or .zshrc:
```bash
source ./ssh-connect/ssh-connect.sh
```

### With [antigen](https://github.com/zsh-users/antigen)

In your .zshrc
```sh
antigen bundle gko/ssh-connect
```

### With [Fig](https://fig.io)

Fig adds apps, shortcuts, and autocomplete to your existing terminal.

Install `ssh-connect` in just one click.

<a href="https://fig.io/plugins/other/ssh-connect_gko" target="_blank"><img src="https://fig.io/badges/install-with-fig.svg" /></a>

## Like it?

:star: this repo

## License

[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2012-2016 Konstantin Gorodinskiy
