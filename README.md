# Settings VSCode Repository

This repository is used to store my custom Visual Studio Code settings, making it easier to sync and back up across different devices.

## Content 

- **settings.json**: Global VSCode settings 
- **extensions.txt**: List of installed extensions

## License

This repository is for personal use, but feel free to take inspiration or adapt the settings as needed.

## How to install 

### Extensions

```
cat vscode-extensions.txt | xargs -n 1 code --install-extension
```

### Settings.json

```
cp settings.json ~/.config/Code/User/settings.json
```
