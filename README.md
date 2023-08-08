# Visual Studio Code configuration

## Symbolic links for using the configuration

Git working directory must be the current working directory for the shell.

### On Linux
```
ln -s $PWD/keybindings.json $HOME/.config/Code/User/keybindings.json
ln -s $PWD/settings.json $HOME/.config/Code/User/settings.json
```

### On Windows as Administrator
```
mklink %APPDATA%\Code\User\keybindings.json %cd%\keybindings.json
mklink %APPDATA%\Code\User\settings.json %cd%\settings.json
```

## VSCode extensions
- [Arduino](https://marketplace.visualstudio.com/items?itemName=vsciot-vscode.vscode-arduino)
- [C/C++](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools)
- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
- [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv)
- [Remote - SSH](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh)

## Fonts
- [Hack](https://sourcefoundry.org/hack/)

## Python packages
- [jedi](https://anaconda.org/conda-forge/jedi)
- [yapf](https://anaconda.org/conda-forge/yapf)
