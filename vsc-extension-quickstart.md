# Welcome to your VS Code Extension

## What's in the folder

- This folder contains all of the files necessary for your color theme extension.
- `package.json` - this is the manifest file that defines the location of the theme file and specifies the base theme of the theme.
- `themes/shades-of-life-color-theme.json` - the color theme definition file.

## Get up and running straight away

- Press `F5` to open a new window with your extension loaded.
- Open the color theme picker with the `File > Preferences > Theme > Color Theme` menu item, or use the `Preferences: Color Theme command (Ctrl+K Ctrl+T)` and pick your theme
- Open a file that has a language associated. The languages' configured grammar will tokenize the text and assign 'scopes' to the tokens. To examine these scopes, invoke the `Developer: Inspect Editor Tokens and Scopes` command from the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac).

## Make changes

- Changes to the theme file are automatically applied to the Extension Development Host window.

## Adopt your theme to Visual Studio Code

- The token colorization is done based on standard TextMate themes. Colors are matched against one or more scopes.

To learn more about scopes and how they're used, check out the [color theme](https://code.visualstudio.com/api/extension-guides/color-theme) documentation.

## Install your extension

- To start using your extension with Visual Studio Code copy it into the `<user home>/.vscode/extensions` folder and restart Code.
- To share your extension with the world, read on <https://code.visualstudio.com/docs> about publishing an extension.

## Package the extention

Install the vsce (Visual Studio Code Extension):

```shell
npm install -g vsce
```

In the terminal, access the folder where your theme is located.

This will create a .vsix file, which is the package for your extension.

```shell
vsce package
```

## Install the extension

### Manual installation

You can install the theme manually from the .vsix file created in the previous step.

- In Visual Studio Code, open the command palette with Cmd + Shift + P (or Ctrl + Shift + P).

- Type Extensions: Install from VSIX... and select the .vsix file you created.

### Using the Extension Store

If you want to publish your theme to other users, you might consider publishing it to the Visual Studio Code Marketplace. You'll need an account and to follow the guide to publishing an extension.

## Activate Theme

After installation, you can activate your theme:

- Vá para as configurações do Visual Studio Code:
- Clique no ícone de engrenagem (⚙️) no canto inferior esquerdo.
- Selecione "Color Theme".
- Na lista de temas, procure "Shades of Life" e selecione-o.
