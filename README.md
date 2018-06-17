# [zsh-jabba][]

[zsh-jabba]:        https://github.com/2m/zsh-jabba

This is a ZSH plugin for [jabba](https://github.com/shyiko/jabba). Together with packaging the original shell integration code required for jabba to work correctly, this plugin also includes autocompletion support for the following commands:

* `use`
* `install`
* `uninstall`

## Installation

### [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)

Clone this repository to `~/.oh-my-zsh/custom/plugins`.

### [antibody](https://getantibody.github.io/)

Add this plugin to the antibody plugins file. Also make sure that the completion functionality in enabled in your `.zshrc` file:

```bash
autoload -U compinit
compinit
```
