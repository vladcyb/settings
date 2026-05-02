# Solarized VS Code Theme

A local extension with a single dark color theme.

## Install

Requires [Node.js](https://nodejs.org/) (includes `npx`). From this folder (where `package.json` lives):

```powershell
npx @vscode/vsce package
```

This creates `solarized-dark-theme-1.0.0.vsix` in the same directory (name and version follow `package.json`). If `vsce` asks for a `publisher` field, add it to `package.json` (e.g. `"publisher": "local"`).

Install the file: **Extensions** → **⋯** → **Install from VSIX…**.

## Development

- Theme file: [`theme.json`](theme.json)
- Extension manifest: [`package.json`](package.json)

For the Extension Development Host, use the **Extension Host** configuration in [`.vscode/launch.json`](.vscode/launch.json) (or create an equivalent manually with `--extensionDevelopmentPath=${workspaceFolder}`).

## License

MIT
