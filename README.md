## Installation

### Option 1: Install from VSIX

Download the latest `.vsix` file from the [Releases](../../releases) page.

Then, in VS Code:

1. Open the Extensions view.
2. Click the `...` menu.
3. Select `Install from VSIX...`.
4. Choose the downloaded `.vsix` file.
5. Open `Preferences: Color Theme`.
6. Select one of the Obscure themes.

### Option 2: Run locally from source

Clone this repository:

```bash
git clone git@github.com:ernandezdev/obscure-theme.git
cd obscure-theme
```

Build the extension package:

```bash
npx @vscode/vsce package --allow-missing-repository
```

Install the generated `.vsix` file:

```bash
code --install-extension obscure-theme-0.1.0.vsix
```

Then open `Preferences: Color Theme` and select one of the Obscure themes.

## Development

To test the theme while editing it, open this repository in VS Code and press `F5`.

This will launch a new Extension Development Host window where you can preview the themes.
