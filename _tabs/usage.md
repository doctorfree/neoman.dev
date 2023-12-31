---
layout: post
post_style: page
toc: true
icon: fas fa-user-circle
order: 2
---

The `neoman` project can be used to install, initialize, configure, and manage

| **Neoman**                           |                **Managed**                 |                  **Project**                   |                                    **Configs** |
| :----------------------------------- | :----------------------------------------: | :--------------------------------------------: | ---------------------------------------------: |
| [Asciiville](#asciiville-management) | [MirrorCommand](#mirrorcommand-management) | [MusicPlayerPlus](#musicplayerplus-management) | [RoonCommandLine](#rooncommandline-management) |
| [Neovim](#neovim-management)         |       [NeoMutt](#neomutt-management)       |        [Newsboat](#newsboat-management)        |                     [Btop++](#btop-management) |
| [Kitty](#kitty-management)           |      [Neofetch](#neofetch-management)      |             [W3m](#w3m-management)             |                       [tmux](#tmux-management) |

These are powerful, configurable, extensible, character-based programs. Neoman
automates the installation, initialization, configuration, and management of
these tools using a command line and character menu interface.

## Asciiville Management

See [https://asciiville.dev](https://asciiville.dev){:target="_blank"}{:rel="noopener noreferrer"}

## MirrorCommand Management

See [https://mirrorcommand.dev](https://mirrorcommand.dev){:target="_blank"}{:rel="noopener noreferrer"}

## MusicPlayerPlus Management

See [https://musicplayerplus.dev](https://musicplayerplus.dev){:target="_blank"}{:rel="noopener noreferrer"}

## RoonCommandLine Management

See [https://rooncommand.dev](https://rooncommand.dev){:target="_blank"}{:rel="noopener noreferrer"}

## Neovim Management

Neoman uses the
[Lazyman Neovim Configuration Manager](https://lazyman.dev){:target="_blank"}{:rel="noopener noreferrer"}
to install [Neovim](https://neovim.io/){:target="_blank"}{:rel="noopener noreferrer"}, tools, and dependencies as well as
multiple Neovim configurations, and the
[Bob](https://github.com/MordechaiHadad/bob){:target="_blank"}{:rel="noopener noreferrer"} Neovim version manager.

<div align="center">
<p float="center">
  <img src="https://raw.githubusercontent.com/wiki/doctorfree/nvim-lazyman/screenshots/lazymenu-transparent.png" alt="Lazyman Neovim Configuration Menu" style="width:900px;height:600px;">
</p>
</div>

## NeoMutt Management

Neoman installs the versatile and highly configurable
[NeoMutt](https://github.com/neomutt/neomutt#readme){:target="_blank"}{:rel="noopener noreferrer"}
command line mail reader (based on Mutt) if not already present
and installs a rich user NeoMutt configuration. The Neoman
NeoMutt configuration can be managed via the `neoman` menu system.

## Newsboat Management

The [Newsboat](https://newsboat.org){:target="_blank"}{:rel="noopener noreferrer"} RSS/Atom feed reader is installed by
Neoman and a rich `newsboat` configuration can be installed using `neoman`.

## Btop Management

The [Btop++](https://github.com/doctorfree/btop#readme){:target="_blank"}{:rel="noopener noreferrer"} system resource monitor
shows usage and stats for processor, memory, disks, network, and processes.
Neoman installs a precompiled `btop` in native package format and provides
a themed `btop` user configuration.

## Kitty Management

The fast, feature-rich, GPU based [Kitty](https://sw.kovidgoyal.net/kitty){:target="_blank"}{:rel="noopener noreferrer"}
terminal emulator is installed and an extensive Kitty configuration made
available by Neoman.

## Neofetch Management

The [Neofetch](https://github.com/dylanaraps/neofetch){:target="_blank"}{:rel="noopener noreferrer"} system information tool is managed
through the `neoman` menu interface.

Many
[Neofetch themes](https://github.com/doctorfree/neoman/blob/main/share/neofetch-themes/README.md){:target="_blank"}{:rel="noopener noreferrer"}
are included in `neoman` thanks primarily to the excellent work of Github user
[Chick2D](https://github.com/Chick2D/neofetch-themes){:target="_blank"}{:rel="noopener noreferrer"}.

## W3m Management

[w3m](https://w3m.sourceforge.net){:target="_blank"}{:rel="noopener noreferrer"} is a text-based web browser as well as a
pager like `more` or `less`. With `w3m` you can browse web pages through a
terminal emulator window (e.g. `kitty`). Moreover, `w3m` can be used as a text
formatting tool which typesets HTML into plain text.

Neoman installs `w3m` and provides an extensive `w3m` configuration which
includes a `mailcap` tailored for use with a character browser.

## Tmux Management

[tmux](https://github.com/tmux/tmux/wiki){:target="_blank"}{:rel="noopener noreferrer"} is a terminal multiplexer. It enables
multiple terminals to be created, accessed, and controlled from a single screen.
Neoman installs `tmux` if not already present and provides an extensive user
`tmux` configuration.
