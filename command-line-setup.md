# Setting Up The Terminal and Command Line

## Homebrew

Homebrew is a package manager that we use to install various command line tools.

Open up the terminal and paste in this command to install Homebew.
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"`

If you are prompted to install Xcode CLI, say yes and homebrew will continue installing.

After the installation process complates, run the command `brew doctor` in your terminal. Resolve any errors and warning before continuing. :) 

Lastly, run `brew update` to make sure all software is up to date.

## Xcode 

Some applications on your Mac may require Xcode libraries. If Xcode CLI was not installed along with homebrew for any reason, you can run this command to install it:
`xcode-select --install`

## Visual Studio Code

Visual Studio Code is our chapter's preferred code editor. We like its features and useful community plug-ins called extensions.

Download and install VS Code from https://code.visualstudio.com/.

Some our favorite extensions:
- prettier
- bracket pair colorizer

## Launch VS Code by typing `code` in the terminal

1. Make sure VS Code is open.
2. Type `shift + command + P` to open the command palette.
3. Start typing `shell command` and when you see<br>`Shell Command: Install 'code' command in PATH` command - click it!
4. Quit VS Code and Terminal.
5. Relaunch Terminal
6. You should now be able to open a folder to edit by typing `code .`

Check [this link](https://code.visualstudio.com/docs/setup/mac) for troubleshooting if you run into issues.

## BASH and Z-Shell

- Check the default cursor of your terminal

- If your cursor is a $, your terminal is using BASH
   - Use oh-my-bash for color-coded and easy-to readp terminal output. 
   - Install oh-my-bash here: https://github.com/ohmybash/oh-my-bash

- If your cursor is a %, your terminal is using Z-Sh (pronounced Z-shell)
   - Use oh-my-zsh for color-coded and easy-to readp terminal output. 
   - Install oh-my-zsh here: https://ohmyz.sh/ 

## Next steps...
* [X] [Command Line](command-line-setup.md)
* [ ] [Installing Git](git-installation.md)
* [ ] [Databases and Frameworks](db-frameworks.md)
* [ ] [Desktop Applications](desktop-applications.md)