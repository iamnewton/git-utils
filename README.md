# git-utils

Just a lot of git functions and scripts I've created and collected over the years.

[![Version 1.0.0](http://img.shields.io/badge/version-1.0.0-brightgreen.svg)](https://github.com/chrisopedia/bash/releases/tag/1.3.0) [![Stories in Ready](https://badge.waffle.io/chrisopedia/git-utils.png?label=Ready)](http://waffle.io/chrisopedia/git-utils)

For the most part, there shouldn't be any dependencies, but each script will have a place at the top that discusses the dependency.

## One-line Install

```bash
$ bash -c "$(curl -#fL raw.github.com/chrisopedia/git-utils/go/install)"
```

## Features

* `git-clean-branches` - Remove all local branches that have been merged into master
* `git-clr-diff` - Diff with color
* `git-hublog` - Git log with per-commit cmd-clickable GitHub URLs (iTerm)
* `git-pr` - Github pull request helper
* `git-rank-contributors` - Script to trace through the logs and rank contributors
* `git-wtf` - Displays the state of your repository in a readable, easy-to-scan format

## Acknowledgements

Inspiration and code was taken from many sources, including (in lexicographical order):

* [@cowboy](https://github.com/cowboy) (Ben Alman) https://github.com/cowboy/dotfiles
* [@jgallen23](https://github.com/jgallen23) (Greg Allen) https://github.com/jgallen23/dotfiles
* [@mathiasbynens](https://github.com/mathiasbynens) (Mathias Bynens) https://github.com/mathiasbynens/dotfiles
* [@necolas](https://github.com/necolas) (Nicolas Gallagher) https://github.com/necolas/dotfiles
* [@wmorgan](https://github.com/wmorgan) (William Morgan)
