# One Half 🎨 🖥

![version tag](https://img.shields.io/github/tag/sonph/onehalf.svg?style=flat-square)
![license tag](https://img.shields.io/github/license/sonph/onehalf.svg?style=flat-square)

A color scheme for Sublime Text, N/Vim, iTerm, and more. Based on Atom's One. Work in progress.

- Name: One Half
- Author: Son A. Pham [@sonph](http://github.com/sonph)
- Url: https://github.com/sonph/onehalf
- License: MIT

**Table of Contents**

- [Features](#features)
- [Screenshots](#screenshots)
- [Installation & Usage](#installation-&-usage)
- [Contributing / Troubleshooting / Bug Reports](#contributing--troubleshooting--bug-reports)
- [License](#license)


## Features
WIP

## Screenshots
(Individual screenshots are available in the [screenshots folder](./screenshots))

### Sublime Text
Sublime Text 3 with Menlo font and [Spacegray](https://github.com/kkga/spacegray) themes.
![screenshot: sublimetext](./screenshots/sublimetext.png)

### (Neo)Vim
NeoVim + Tmux with true colors support on iTerm2.
![screenshot: vim](./screenshots/vim.png)

### iTerm
![screenshot: terminal](./screenshots/iterm.png)


## Installation & Usage
### Vim
Install with Vundle then set `colorscheme` and `g:airline_theme`:

    Bundle 'sonph/onehalf', {'rtp': 'vim/'}
    colorscheme onehalflight
    let g:airline_theme='onehalfdark'

([details/manual installation](./vim/README.md))


### Sublime Text 2/3
Install with [Package Control](https://packagecontrol.io).

([details/manual installation](./sublimetext/README.md))


### iTerm2
1. Download color themes in the [iterm](./iterm) folder
2. Import the color themes
	- _Either_ double click on the color scheme files to import
	- _Or_ open iTerm Preferences > Profiles > Colors > Color Presets > Import
	and select the downloaded color theme files
3. Select Preferences > Profiles > Colors > Color Presets > One Half Light (Dark)


## Contributing / Troubleshooting / Bug Reports
Contributions are welcome. Feel free to [open an issue](https://github.com/sonph/onehalf/issues/new)
if you have problems installing and using the colorschemes.


## License
Released under the MIT license.