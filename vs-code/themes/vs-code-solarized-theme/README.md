# Solarized VS Code Theme

A local extension with a single dark color theme.

## Install from the project folder

1. Open this folder in **VS Code** or **Cursor**.
2. Choose **Run** → **Start Debugging** (`F5`), or use the Command Palette → **Developer: Reload Window** after packaging.

Or install via the CLI (if `code` is on your PATH):

```powershell
code --install-extension .
```

Open the Command Palette (`Ctrl+Shift+P`) → **Preferences: Color Theme** → **Solarized VS Code Theme**.

## Development

- Theme file: [`themes/theme.json`](themes/theme.json)
- Extension manifest: [`package.json`](package.json)

For the Extension Development Host, use the **Extension Host** configuration in [`.vscode/launch.json`](.vscode/launch.json) (or create an equivalent manually with `--extensionDevelopmentPath=${workspaceFolder}`).

## License

MIT
