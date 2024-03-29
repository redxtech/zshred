# [zshred][repo-link]
> A theme for zsh via [oh-my-zsh][omz-link].

## Notice
I have replaced this theme with a configuration of [powerlevel19k][p10k-link], which you can find
in my [dotfiles][dotfiles-link].

[![MIT License](https://img.shields.io/github/license/redxtech/zshred)](/LICENSE)
[![oh-my-zsh](https://img.shields.io/github/stars/robbyrussell/oh-my-zsh?label=oh-my-zsh)][omz-link]

## install
> There's probably a better way to do it, but this will get the job done.

```zsh
$ git clone https://github.com/redxtech/zshred.git
$ cp zshred/themes/zshred.zsh-theme $ZSH_CUSTOM/themes/
```

## features

* current directory shown in prompt
* full path shown in right prompt
* git branch and status shown
* exit status shown in right prompt
* current time shown in right prompt
* title set to current prompt
* even more!

## screenshot

<p align="center">
<img src="https://i.imgur.com/6dogeQJ.png" alt="Image in which I meant to exclude -rf to show the exit code of a failed command">
</p>

### screenshot details
* terminal emulator: [`alacritty`][alacritty]
* terminal colour scheme: [one dark][a-one-dark]
* status bar: [tmux one dark theme][tmux-one-dark]
* syntax highlighting: [zsh-syntax-highlighting][syntax]

## author

**zshred** © [redxtech][author], released under the [MIT][mit] license.

[mit]:              https://opensource.org/licenses/MIT
[author]:           https://github.com/redxtech
[omz-link]:         https://github.com/robbyrussell/oh-my-zsh
[repo-link]:        https://github.com/redxtech/zshred
[alacritty]:        https://github.com/jwilm/alacritty
[a-one-dark]:       https://github.com/jwilm/alacritty/wiki/Color-schemes#one-dark
[tmux-one-dark]:    https://github.com/odedlaz/tmux-onedark-theme
[syntax]:           https://github.com/zsh-users/zsh-syntax-highlighting
[p10k-link]:        https://github.com/romkatv/powerlevel10k
[dotfiles-link]:    https://github.com/redxtech/dotfiles/blob/master/.config/zsh/p10k.zsh

