# Teedo Menu: AHK Script for Call of Duty

# Some of the releases are not in order, so scrolling through all releases is a must.

## Overview
This AutoHotkey script, **Teedo Menu**, is a utility designed to enhance gameplay with various features such as recoil control, lock-on targeting, triggerbot, FOV (Field of View) display, dropshot functionality, and predictive aiming. It features a GUI (Graphical User Interface) that allows easy configuration and control of these features.

The script provides a range of customization options for the user to tailor their experience, including the ability to adjust recoil control, dot color, field of view, and more. Additionally, the script has several modes like Zombies Mode, Shotgun Mode, and Multiplayer Mode that are activated through simple toggle options in the menu.

## Features
- **Dot Color**: Adjust the target dot color using a hexadecimal color code.
- **FOV (Field of View)**: Customize the FOV width and height.
- **Recoil Control**: Control recoil during aiming to ensure better accuracy.
- **Lock-On Strength**: Set the strength of the lock-on aiming functionality.
- **Predictive Aiming**: Enable predictive aiming to account for target movement.
- **Zombies Mode**: Customize offsets for zombie-themed gameplay.
- **Dropshot Mode**: Automatically drops to the floor when the right mouse button (RMB) is pressed.
- **Shotgun Mode**: Automatic shooting without holding RMB.
- **Triggerbot**: Automatically shoots when the target dot is over an enemy.
- **Multiplayer Mode**: Use multiplayer-specific offsets and behaviors.
- **Interactive Menu**: Toggle settings through an easy-to-use graphical interface.
- **Visibility**: Toggle the display of the menu and FOV overlay.
- **Configuration**: Customize the script's behavior through a user-friendly menu interface.

## Prerequisites
- **AutoHotkey**: The script requires AutoHotkey to run. You can download it from [AutoHotkey Official Site](https://www.autohotkey.com/).

## Installation Instructions
1. Download and install AutoHotkey.
2. Save the script as `MenuX.X.X.exe` (this is required for the script to function correctly).
3. Double-click the `MenuX.X.X.exe` to start the script.
4. The `X.X.X` depends on the version of which you downloaded. Basically keep the name the same.

## Script Usage
### Hotkeys:
- **Script Toggle** (`Home`): Show or hide the main menu.
- **Enable/Disable Script** (`\`): Toggle the main functionality of the script. If enabled, the script will actively control the mouse and perform functions like triggerbot and recoil control.
- **Enable/Disable Predictive Aiming** (`Ins`): Toggle predictive aiming mode, which adjusts the aim based on target movement.
- **Enable/Disable FOV** (`0`): Toggle the display of the field of view (FOV) window.

### Menu Settings
The script provides a user-friendly interface with two main pages:

1. **Page 1 (Main Settings)**: Allows you to adjust the Dot Color, FOV width, FOV height, Recoil Control, Default Offset, and Lock-On Strength.
2. **Page 2 (Toggle Settings)**: Includes options to toggle FOV Display, Triggerbot, Zombies Mode, Dropshot Mode, Shotgun Mode, and Multiplayer Mode.

### Features Explained:
- **Dot Color (Hex)**: Specify the color of the target dot in hexadecimal format (e.g., 0xDF00FF for purple).
- **FOV Width/Height**: Define the scanning area for the dot detection.
- **Recoil Control**: Use a value between 0.0 and 1.0 to control how much recoil is compensated.
- **Lock-On Strength**: Adjust the strength of the script’s auto-lock-on functionality.
- **Zombies Mode**: Automatically adjusts the offset for zombie-themed gameplay, positioning the crosshairs differently.
- **Dropshot Mode**: When enabled, the script automatically drops the character to the ground by pressing the "C" key when the right mouse button (RMB) or LT (Axis Z) is pressed.
- **Shotgun Mode**: Automatically fires repeatedly when activated (suitable for shotgun play).
- **Triggerbot**: Automatically shoots when an enemy is detected under the targeting dot.

## Controller Support

- **Controller Support**: The script supports controller input for specific features, including:
  - **Triggerbot**: Works with controllers for automatic shooting when the target is aligned.
  - **Dropshot Mode**: Automatically drops the character when the right trigger (or equivalent button) is pressed.
  - **Shotgun Mode**: Automatically fires repeatedly when activated, ideal for controller users.

Currently, we're working on updates for the **Aim Lock** feature, and any new updates will be posted in the [Discord Server](https://dsc.gg/143x) before being made available on the GitHub page. Some features may not work as expected.


## Troubleshooting
If you encounter issues or the script isn't functioning as expected:

- Ensure the script is named `Menu3.0.0.exe`. If it isn't, rename it to match the required filename.
- Double-check that AutoHotkey is installed and correctly configured on your system.
- Ensure that your game settings are configured properly to allow the script to interact with the screen and detect pixels.
- Ensure you enable FOV in the menu settings or this will cause mouse movements to spaz out.
- Ensure you're on 1920x1080p resolution, desktop and game. (May work on other resolutions).
- Ensure Enemy Names in the options are set to Icon Only.
- Ensure Enemy Colour in game is set to #DF00FF.

## License
This script is provided as-is with no guarantees. The creator is not responsible for any consequences of using the script, including but not limited to bans from game servers or any other unintended effects.

## Contact
- **YouTube**: [Teedo](https://youtube.com/qwoah)
- **Discord**: [Discord Server](https://dsc.gg/143x)
- **JOIN THE DISCORD IF INTERESTED IN BUYING OUR HWID SPOOFER. PREVENTS HWID BANS/UNBANS HWID'S FOR TIME GIVEN**
