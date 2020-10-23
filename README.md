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

## VSCode Extensions
- Arduino
- C/C++
- Code Spell Checker
- LaTeX Workshop
- One Dark Pro
- Pylance
- Python
- Rainbow CSV
- Remote - SSH
- Remote - SSH: Editing Configuration Files

## Fonts required
- [Hack](https://sourcefoundry.org/hack/)

## Python libraries required
- Pylint
- Rope
- Yapf
