# Darcula Theme from IntelliJ — Antigravity

Antigravity-ready packaging of the original Darcula IntelliJ theme.
The theme provides an IntelliJ-style Darcula color scheme, including syntax-specific font styling.

## Installation

### Build from source

Clone the repository:

```bash
git clone https://github.com/raginsky/darcula-intellij-theme-antigravity.git
cd darcula-intellij-theme-antigravity
```

Install the development dependencies:

```bash
npm install
```

Package the extension:

```bash
npm run package
```

This creates:

```text
dracula-theme-from-intellij-0.3.0.vsix
```

Install the package in Antigravity:

```bash
antigravity-ide --install-extension dracula-theme-from-intellij-0.3.0.vsix
```

### Install from a release

Download the latest `.vsix` from [GitHub Releases](https://github.com/raginsky/darcula-intellij-theme-antigravity/releases) and install it:

```bash
antigravity-ide --install-extension dracula-theme-from-intellij-0.3.0.vsix
```

No build step is required when using the packaged `.vsix`.

## Development

The extension uses `@vscode/vsce` for packaging.

```bash
npm run package
```

The package script is equivalent to:

```bash
vsce package
```

## Original theme

Created by Minh Tri Nguyen.

- Original repository: [kevinvn1709/vscode-dracula-color-theme](https://github.com/kevinvn1709/vscode-dracula-color-theme)
- Visual Studio Marketplace publisher: `trinm1709`
- Extension ID: `trinm1709.dracula-theme-from-intellij`

This repository preserves the original theme while providing a convenient way to package and install it in Antigravity.

## License

MIT. See [LICENSE](LICENSE).
