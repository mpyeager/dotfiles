# Universal environment .dotfiles for Mac

1. [zshrc](https://github.com/mpyeager/dotfiles/blob/main/zshrc)
Used to modify [ZSH](https://en.wikipedia.org/wiki/Z_shell) and to support custom themes from [OhMyZSH][1].
Following [OhMyZsh][1] [plugins][2] are used:
* [bazel](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/bazel "Build and test tool open sourced from Google blaze")
* [brew](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/brew "Package manager for MacOS")
* [chucknorris](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/chucknorris "No day is complete without a Chuck Norris quote")
* [command-not-found](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/command-not-found "Automagically suggest packages to be installed if a command no worky")
* [copyfile](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/copyfile "Puts contents of file to system clipboard")
* [copypath](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/copypath "Copy absolute path of given directory or file to system clipboard")
* [fig](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/fig "Sets up auotmagical completion a la Fig")
* [flutter](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/flutter "Completion and aliases for Flutter")
* [fzf](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/fzf "Fuzzy auto-completion and key bindings")
* [git](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/git "Aliases and useful functions for git")
* [golang](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/golang "Completion and aliases for common Golang commands")
* [history](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/history "Aliases for using history command to examine command line history")
* [mercurial](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/mercurial "Aliases, utility and prompt functions for using Mercurial")
* [thefuck](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/thefuck "Corrects previous command using ESC x2")
* [vscode](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/vscode "Aliases for VScode")
* [zsh-interactive-cd](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/zsh-interactive-cd "Adds fish-like interactive tab completion")

2. [bullet-train](https://github.com/mpyeager/dotfiles/blob/main/bullet-train) used to augment [OhMyZSH theme](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes) [Bullet Train](https://github.com/caiogondim/bullet-train.zsh)

## Not a dotfile, but pretty damn useful
1. [trash](https://hasseg.org/trash/) which can be installed with [Homebrew]("brew install trash"), then `alias rm='trash'` to tell your system that you want to use `trash` instead of `rm`. Don't worry, you can always use `\rm` if you want to use the native `rm`.
2. [z](https://github.com/rupa/z "This will change your life!") is hugely useful as it creates a local database to record most frequently accessed directories when using `cd`. 
[1]: https://ohmyz.sh
[2]: https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins