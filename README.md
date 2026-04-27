# Obscure Theme

A focused collection of dark VS Code themes with matching file icon themes.

Obscure Theme is designed for developers who prefer a clean, minimal, and comfortable dark editor experience, with carefully balanced syntax colors and matching file icons for daily coding.

## Included Themes

### Color Themes

- Obscure Noir
- Obscure Ember
- Obscure Mist

### File Icon Themes

- Obscure File Icons
- Obscure File Icons Mono

## Usage

### Color Themes

Open the Command Palette and run:

```txt
Preferences: Color Theme
```

Then select:

- Obscure Noir
- Obscure Ember
- Obscure Mist

### File Icon Themes

Open the Command Palette and run:

```txt
Preferences: File Icon Theme
```

Then select:

- Obscure File Icons
- Obscure File Icons Mono

## Installation

### Option 1: Install from VSIX

Download the latest `.vsix` file from the [Releases](https://github.com/ernandezdev/obscure-theme/releases) page.

Then, in VS Code:

1. Open the Extensions view.
2. Click the `...` menu.
3. Select `Install from VSIX...`.
4. Choose the downloaded `.vsix` file.
5. Open `Preferences: Color Theme` or `Preferences: File Icon Theme`.
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
code --install-extension obscure-theme-*.vsix
```

## Development

To test the theme while editing it, open this repository in VS Code and press `F5`.

This will launch a new Extension Development Host window where you can preview the themes.

## Credits

The file icon themes include assets based on File Icons and are used according to their original license.

See `THIRD_PARTY_LICENSES.md` for details.

## License

MIT
