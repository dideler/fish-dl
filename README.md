# fish-dl [![CircleCI](https://circleci.com/gh/dideler/fish-dl.svg?style=svg)](https://circleci.com/gh/dideler/fish-dl)

Opinionated wrapper around youtube-dl to easily download audio when using the [fish shell].

All downloads get saved as MP3 in the `$HOME/Music` directory, with a filename from the content's title.

## Demo

![Example usage of fish-dl](https://user-images.githubusercontent.com/497458/66087331-02a4dc00-e56f-11e9-936c-d1f6177a1c84.gif)

Works with any youtube-dl supported source.

## Install

Install with your favourite fish package manager, such as [fisherman] or [oh-my-fish]

```shell
# Install with fisher v3
fisher add dideler/fish-dl

# Install with fisher v2
fisher install dideler/fish-dl

# Install with oh-my-fish
omf install https://github.com/dideler/fish-dl
```

## Usage

```fish
dl "https://www.youtube.com/watch?v=hC8CH0Z3L54"
```

## Goals

I love youtube-dl, it's a very powerful tool. At the time of writing (2018-07-22), the project can extract media from 750+ different sources, its man page is ~3000 lines long, its help output is ~300 lines long, and it has ~120K lines of code.

But 99% of the time, I use it for dowloading music, and got tired of its complicated API and configuration.

This is an opinionated wrapper to download audio as MP3 with a good enough filename to a specific directory.


[fisherman]: https://github.com/fisherman/fisherman
[oh-my-fish]: https://github.com/oh-my-fish/oh-my-fish
[fish shell]: https://fishshell.com/
