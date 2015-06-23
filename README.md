Monokai Colorscheme
----------------

The Monokai color scheme for:

Terminal, iTerm, KDE Konsole, Kate, VIM, Emacs, Atom, VisualStudio

## Installation

#### MacOSX Terminal and iTerm

1. Clone the repository `git clone git://github.com/tommodore/monokai.git`.
2. Open the `Monokai.terminal` or `Monokai.itermcolors` file to install.
3. Optionally open up Terminal or iTerm  preferences for more options.

#### KDE Konsole

1. Copy the Konsole colorscheme (*.colorscheme) files to ~/.kde/share/apps/konsole/.
2. Open Konsole and select Settings => Configure Profiles => Edit Profile => Appearance.
3. Select the Monokai scheme file and save.

#### KDE Kate

1. Open Kate and select Configurations => Configure Kate => Fonts and Colours
2. Import and Select the Monokai scheme file and save.

#### Emacs

1. Download `monokai-theme.el` to the directory `~/.emacs.d/themes/`
2. Add this to your .emacs: `(add-to-list 'custom-theme-load-path "~/.emacs.d/themes/")`
3. Now you can load the theme with the interactive function `load-theme` like this: `M-x load-theme RET monokai`

Or simply use [Marmelade](http://marmalade-repo.org/) or [MELPA](http://melpa.milkbox.net/)

#### VIM

Put `monokai.vim` file in your `~/.vim/colors/` directory and add the following line to your `~/.vimrc`:

    syntax enable
    colorscheme monokai


Or simply use [vim-monokai](https://github.com/sickill/vim-monokai) module from [sickill](https://github.com/sickill) with [Vundle](https://github.com/gmarik/Vundle.vim).

#### Atom

Simply use [monokai](https://github.com/kevinsawicki/monokai) module from [kevinsawicki](https://github.com/kevinsawicki).

#### Visual Studio

1. To apply, go to `Tools` -> `Import and Export Settings` -> Import selected environment settings.

## License

This project is not licensed and is free for anyone to use.

## Credit

Monokai Terminal and iTerm theme created by [Stephen Way](https://github.com/stephenway).

The Monokai color scheme was created by Wimer Hazenberg, http://monokai.nl

