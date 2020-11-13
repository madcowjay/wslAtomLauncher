# wsl Atom Launcher
wsl Atom Launcher is a simple script used to launch the Windows version of Atom from within the Ubuntu wsl. It is based on Eduardo's answer here: https://stackoverflow.com/questions/56976845/how-to-start-atom-or-vscode-natively-installed-on-windows-from-within-wsl-ubunt

## Installation
1. Simply place the atom binary in your ~/.local/bin folder
2. Make sure ~/.local/bin is in your path
3. Restart your shell

## Usage
```bash
atom # Opens a new Atom window
atom <argument> # Opens the given folder or file in Atom
```
