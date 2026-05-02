# VS Code/Cursor Themes

This directory contains one or more theme extensions.  
Each theme extension lives in its own subfolder and includes a `package.json`.

## Build a theme package (`.vsix`)

Prerequisite: [Node.js](https://nodejs.org/) (includes `npx`).

From the specific theme folder (the one that has `package.json`), run:

```powershell
npx @vscode/vsce package
```

This creates a `.vsix` file in the same folder.  
The filename is based on `name` + `version` from `package.json`.

## Install a theme package

In VS Code or Cursor:

1. Open **Extensions**.
2. Click **⋯** (More Actions).
3. Select **Install from VSIX...**.
4. Choose the generated `.vsix` file.

Then open **Preferences: Color Theme** and select the installed theme.

## Development mode (without packaging)

To test a theme while editing:

1. Open the theme extension folder in VS Code/Cursor.
2. Run **Start Debugging** (`F5`) to launch an Extension Development Host.
3. In the new window, switch the active color theme.

