# yarn-plugin-list

> A modern Yarn plugin to reimplement the `list` command from Yarn v1

The initial version of this plugin is only intended to work around a limitation
in VSCE that causes it to fail when attempting to publish VS Code Extensions
using Yarn v3. For more information, see:
https://github.com/microsoft/vscode-vsce/issues/517

Just install this plugin into your project, and you'll be able to publish your
VS Code Extension as you normally would.

## Installation

Add this plugin by running:

```
yarn plugin import https://github.com/arendjr/yarn-plugin-list/releases/latest/download/yarn-plugin-list.js
```

## Contributions

Run `yarn` to install everything you need. Before opening a PR, please run
`yarn format` and `yarn lint` to make sure your code is formatted correctly and
passes the linter.

## License

[MIT](LICENSE)
