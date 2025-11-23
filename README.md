# NumpadLauncher

A simple, efficient utility to launch applications and execute shortcuts using your Numpad.

## Features
-   **App Launching**: Assign applications or folders to numpad keys.
-   **Shortcut Mapping**: Map complex key combinations (e.g., Ctrl+Shift+T) to a single numpad key.
-   **Background Operation**: Runs quietly in the system tray.
-   **Startup Support**: Option to launch automatically with Windows.

## Installation

No installation is required. Simply download the executable for your system architecture from the `releases` folder.

### Available Versions
-   **x64**: For standard 64-bit Windows systems.
-   **x86 (x32)**: For 32-bit Windows systems.
-   **arm64**: For Windows on ARM devices.

## Usage
1.  Run `NumpadLauncher.exe`.
2.  The application will appear in your system tray.
3.  Right-click the tray icon to open the configuration window.
4.  Click on a Numpad key in the UI to assign an action.
5.  Choose between "Application/Folder" or "Key Combination".
6.  Click "Save".

## Building from Source
1.  Open `src/NumpadLauncher.sln` in Visual Studio.
2.  Restore NuGet packages.
3.  Build the solution.
