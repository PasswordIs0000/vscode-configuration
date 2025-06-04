# Visual Studio Code configuration

## Symbolic links for using the configuration

Git working directory must be the current working directory for the shell.

### On Linux
```
ln -s $PWD/keybindings.json $HOME/.config/Code/User/keybindings.json
ln -s $PWD/settings.json $HOME/.config/Code/User/settings.json
```

### On Windows as an administrator
```
mklink %APPDATA%\Code\User\keybindings.json %cd%\keybindings.json
mklink %APPDATA%\Code\User\settings.json %cd%\settings.json
```

## VSCode extensions
- [Black Formatter](https://marketplace.visualstudio.com/items?itemName=ms-python.black-formatter)
- [C/C++](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools)
- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- [German - Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker-german)
- [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)
- [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
- [Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)
- [Pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance)
- [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
- [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv)
- [Remote - SSH](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh)

## Fonts
- [Hack](https://sourcefoundry.org/hack/)

## Tips & Tricks

### i3wm and missing Github login
Add this to the *~/.vscode/argv.json* file:
```
"password-store": "gnome-libsecret"
```