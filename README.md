# Darcula Theme from IntelliJ — Antigravity

Antigravity-ready packaging of the original Darcula IntelliJ theme by kevinvn1709 / trinm1709.

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

If a packaged `.vsix` is available in GitHub Releases, download it and install it directly:

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

## Original extension

Original publisher: `kevinvn1709`

Extension ID:

```text
kevinvn1709/vscode-dracula-color-theme
```

This repository preserves the original theme while providing a convenient way to package and install it in Antigravity.

## License

MIT. See [LICENSE](LICENSE).
