# User Documentation - ReloadEditor Plugin

## Overview

**ReloadEditor** is a simple yet powerful plugin for Unreal Engine that allows you to quickly restart the editor without having to close and relaunch it manually. This saves you valuable time during development sessions.

## Installation

### Via Epic Games Marketplace

1. Add the plugin to your library
2. In the Epic Games Launcher, install the plugin
3. In your project, enable the plugin via the **Edit > Plugins** menu
4. Restart the editor when prompted

### Manual Installation

1. Download the plugin
2. Extract it into the `Plugins` folder of your project
3. Restart the editor
4. Enable the plugin via the **Edit > Plugins** menu

## Usage

After installation, you can access the plugin in two ways:

- **In the Window menu**: A "Restart Editor" button appears
- **In the main toolbar**: A dedicated button for quickly restarting the editor

### Configuration Options

Access the options menu by clicking on the button on the right (three dots).:

- **Auto save before reload**: Automatically saves all modified files before restarting
- **Auto reload last map opened**: Automatically reloads the last opened map after restart
- **Change shortcut**: Allows you to set a custom keyboard shortcut to restart the editor (Default shartuct is "CTRL + SHIFT + R")

## Key Features

### Quick Restart
Simply click the button to instantly restart the editor.

### Auto Save
When this option is enabled, all your unsaved files will be automatically saved before restarting.

### Map Reloading
The "Auto reload last map" option automatically reopens the map you were working on before the restart.

### Custom Shortcuts
Configure your own key combination to restart the editor even faster.

## Compatibility

- **Supported Unreal Engine versions**: 5.4.0 to 5.5.0
- **Platforms**: Windows, Mac and Linux
- **Type**: Editor-only plugin (not available in game builds)

## Troubleshooting

### The plugin doesn't appear
- Check that the plugin is enabled in **Edit > Plugins**
- Make sure your Unreal Engine version is compatible (5.4.0 - 5.5.0)

### The editor doesn't restart properly
- Verify that you have administrator rights on your system
- Make sure no UE process is blocking the restart
