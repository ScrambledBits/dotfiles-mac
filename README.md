# MacOS Dotfile Documentation

This documentation will cover the various dotfiles that can be used on a MacOS system.

## .zshrc

The `.zshrc` file is a configuration file for the zsh shell. It is executed each time a new terminal session is started, and allows for customization of the shell environment. Users can set aliases, define functions, and configure various shell options to fit their preferences. The `.zshrc` file can also be used to load plugins and themes, further extending the functionality of the shell.


## .vimrc

The `.vimrc` file is a configuration file for the Vim text editor. It allows users to customize various settings and mappings within the editor such as colorschemes, syntax highlighting, and key bindings. The `.vimrc` file is located in the user's home directory and is read by `Vim` upon startup. It can be edited manually or with the use of third-party plugins.

## .config/starship.toml

The `starship.toml` file is a configuration file for the [Starship prompt](https://starship.rs/), a fast and customizable command-line prompt for Unix-like systems. The file is written in the TOML format, and it allows you to customize various aspects of the prompt, such as the prompt format, colors, icons, and more. With this file, you can create a personalized prompt that suits your workflow and style. The `starship.toml` file also supports dynamic configuration based on the current context, such as the current working directory, Git branch, or Docker container. This allows you to display relevant information on the prompt, and switch between different configurations as needed.

## .config/nvim/init.vim

The `init.vim` file is a configuration file for the [Neovim](https://neovim.io/) text editor. It allows users to customize various settings and mappings within the editor such as colorschemes, syntax highlighting, and key bindings. The `init.vim` file is located in the user's home directory and is read by `Neovim` upon startup. It can be edited manually or with the use of third-party plugins.

## .gitconfig

The `.gitconfig` file is a configuration file for the [Git](https://git-scm.com/) version control system. It allows users to customize various settings and mappings within the editor such as colorschemes, syntax highlighting, and key bindings. The `.gitconfig` file is located in the user's home directory and is read by `Git` upon startup. It can be edited manually or with the use of third-party plugins.

## .gitignore_global

The `.gitignore_global` file is a configuration file for the [Git](https://git-scm.com/) version control system to specify files and directories that should not be tracked by Git during version control. This file contains a list of file patterns that Git should ignore when performing operations like adding files to the repository or performing a commit. Common examples of files to ignore include compiled binaries, log files, and temporary files. The .gitignore file can be placed in the root directory of a project or in any subdirectory within the project.
