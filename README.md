# VS Code Settings
This repository stores my personal Visual Studio Code settings. Feel free to use or adapt these settings for your own setup.

## Contents
- `settings.json`: Custom VS Code settings.
- `extensions.txt`: List of extensions.

## How to Use
### settings.json
1. Clone this repository.
2. Copy the `settings.json` to your VS Code user settings directory:
   - **Windows**: `%APPDATA%\Code\User\`
   - **macOS**: `~/Library/Application Support/Code/User/`
   - **Linux**: `~/.config/Code/User/`
3. Restart VS Code to apply the settings.

### extension.txt
1. Clone this repository.
2. Install with command:
   - **Windows**: ```Get-Content extensions.txt | ForEach-Object { code --install-extension $_ }```
   - **Linux**: ```xargs -a extensions.txt -n 1 code --install-extension```

## How to Get
### settings.json
Copy the `settings.json` from VS Code user settings directory:
   - **Windows**: `%APPDATA%\Code\User\`
   - **macOS**: `~/Library/Application Support/Code/User/`
   - **Linux**: `~/.config/Code/User/`

### extension.txt
Write in cmd ```code --list-extensions > extensions.txt```
