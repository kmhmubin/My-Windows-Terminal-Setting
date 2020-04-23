# My-Windows-Terminal-Setting
Personal New Windows Terminal Settings

## Preview Image
![Preview Image](https://github.com/kmhmubin/My-Windows-Terminal-Setting/blob/master/Preview.png)


## Profile Setting

```
// To view the default settings, hold "alt" while clicking on the "Settings" button.
// For documentation on these settings, see: https://aka.ms/terminal-documentation
{
  "$schema": "https://aka.ms/terminal-profiles-schema",
  "defaultProfile": "{0caa0dad-35be-5f56-a8ff-afceeeaa6101}",
  "profiles": {
    "defaults": {
      // Put settings here that you want to apply to all profiles
      "copyOnSelect": true
    },
    "list": [
      {
        // Make changes here to the powershell.exe profile
        "guid": "{61c54bbd-c2c6-5271-96e7-009a87ff44bf}",
        "name": "Windows PowerShell",
        "commandline": "powershell.exe",
        "hidden": false,
        "startingDirectory": "%USERPROFILE%",
        "closeOnExit": true,
        "colorScheme": "Solarized Light",
        "foreground": "#DCDFE4",
        "background": "#282C34",
        "fontFace": "JetBrains Mono",
        "fontSize": 14,
        "historySize": 9001,
        "snapOnInput": true,
        "useAcrylic": true,
        "acrylicOpacity": 0.75
      },
      {
        // Make changes here to the cmd.exe profile
        "guid": "{0caa0dad-35be-5f56-a8ff-afceeeaa6101}",
        "name": "cmd",
        "commandline": "cmd.exe",
        "hidden": false,
        "startingDirectory": "%USERPROFILE%",
        "closeOnExit": true,
        "colorScheme": "Solarized Light",
        "foreground": "#DCDFE4",
        "background": "#282C34",
        "fontFace": "JetBrains Mono",
        "fontSize": 14,
        "historySize": 9001,
        "snapOnInput": true,
        "useAcrylic": true,
        "acrylicOpacity": 0.75
      },
      {
        "guid": "{b453ae62-4e3d-5e58-b989-0a998ec441b8}",
        "hidden": false,
        "name": "Azure Cloud Shell",
        "source": "Windows.Terminal.Azure"
      }
    ]
  },
  // Add custom color schemes to this array
  "schemes": [],
  // Add any keybinding overrides to this array.
  // To unbind a default keybinding, set the command to "unbound"
  "globals": {
    "keybindings": [
      {
        "command": "copy",
        "keys": ["Ctrl+C"]
      },
      {
        "command": "paste",
        "keys": ["Ctrl+V"]
      },
      {
        "command": "newTab",
        "keys": ["Ctrl+T"]
      },
      {
        "command": "closeTab",
        "keys": ["Ctrl+W"]
      },
      {
        "command": "duplicateTab",
        "keys": ["Ctrl+D"]
      },
      {
        "command": "nextTab",
        "keys": ["Ctrl+Tab"]
      },
      {
        "command": "prevTab",
        "keys": ["Ctrl+Shift+Tab"]
      },
      {
        "command": "find",
        "keys": ["Ctrl+F"]
      }
    ]
  }
}


```