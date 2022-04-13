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
- Arduino
- C/C++
- Code Spell Checker
- German - Code Spell Checker
- Jupyter
- Jupyter Keymap
- Jupyter Notebook Renderers
- LaTeX Workshop
- Pylance
- Python
- Rainbow CSV
- Remote - SSH
- Remote - SSH: Editing Configuration Files

## Fonts
- [Hack](https://sourcefoundry.org/hack/)

## Python packages
- ipykernel
- pylint
- rope
- yapf
