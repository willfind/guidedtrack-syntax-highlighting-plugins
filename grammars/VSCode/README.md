# Installation

Follow these steps to install the GuidedTrack syntax highlighter plugin in VSCode:

1. Clone (or download and extract) this repository.
2. Open VSCodium.
3. Open the command palette (probably using Ctrl+Shift+P or Cmd+Shift+P unless you've changed the key bindings).
4. Type "vsix" to search for the relevant command.
5. Select the "Extensions: Install from VSIX..." command.
6. Use the file browser to navigate to and select the `guidedtrack.vsix` file in this directory.

See [this page](https://code.visualstudio.com/docs/editor/extension-marketplace#_install-from-a-vsix) in the VSCode docs for more information about installing plugins via `*.vsix` files.

# Note to developers

Developers, if you make changes to this plugin, please be sure to re-package the `guidedtrack.vsix` file in this directory so that end-users following the above steps will receive the latest changes. The re-packaging process is pretty simple. The steps are:

1. Install Microsoft's [VSCode Extension Manager](https://github.com/microsoft/vscode-vsce) tool:

```bash
npm install -g vsce
```

2. From within this directory, run the VSCode Extension Manager to package the plugin into a single `*.vsix` file:

```bash
vsce package
```

3. When it's finished, `vsce` should print out the location of the new `*.vsix` file. The file name will usually include the version number (e.g., `guidedtrack-0.0.1.vsix`). Please remove the version number so that the file name is just `guidedtrack.vsix`.

4. Commit your changes (including the new `guidedtrack.vsix` file) and push them to GitHub.
