# Welcome to the Arwinux Galaxy VS Code Theme Extension

This guide will help you get started with developing, testing, and eventually publishing your Arwinux Galaxy theme for Visual Studio Code.

---

## What's in the Folder

- **package.json**  
  The manifest file that defines your extension, its contributions (like the theme file), and metadata (name, description, version, etc.).

- **themes/Arwinux Galaxy-color-theme.json**  
  The color theme definition file. This file contains all the colors and styling rules for your theme.

- **Other files (if any)**  
  Additional documentation or assets such as icons, screenshots, or changelogs can be added here.

---

## Getting Up and Running

1. **Launch the Extension Development Host:**
   - Press `F5` to open a new VS Code window with your extension loaded in development mode.

2. **Activate Your Theme:**
   - Open the Command Palette (`Ctrl+Shift+P` on Windows/Linux or `Cmd+Shift+P` on macOS) and run the command: `Preferences: Color Theme`.
   - Select **Arwinux Galaxy** from the list of available themes.

3. **Explore the Theme in Action:**
   - Open a file that uses a recognized language grammar.
   - To inspect how your theme applies colorization, run the command `Developer: Inspect Editor Tokens and Scopes` from the Command Palette.

---

## Making Changes

- **Live Reloading:**  
  Any changes you make to the theme file (`themes/Arwinux Galaxy-color-theme.json`) are automatically applied to the Extension Development Host window. Simply save your changes and see them take effect immediately.

- **Customization Tips:**  
  - The theme uses standard TextMate scopes for token colorization. You can adjust the colors by editing the JSON file.
  - For more details on customizing color themes, refer to the [Visual Studio Code Color Theme documentation](https://code.visualstudio.com/api/extension-guides/color-theme).

---

## Adopting Your Theme

- **Understanding Scopes:**  
  VS Code uses TextMate grammars to tokenize source code and assign scopes. Your theme matches colors to these scopes. Experiment with different scopes using the "Inspect Editor Tokens and Scopes" command to fine-tune your theme.

- **Tweaking Colors:**  
  You can update colors, add new rules, or remove unused ones in your JSON theme file to better match your vision of a "galaxy" inspired aesthetic.

---

## Installing and Publishing Your Extension

- **Local Installation:**
  - To try out your theme outside of the Extension Development Host, copy the entire project folder into the `<user home>/.vscode/extensions` directory.
  - Restart VS Code, then open the theme picker to select **Arwinux Galaxy**.

- **Publishing Your Extension:**
  - When you’re ready to share your theme with the world, follow the official [Visual Studio Code Publishing Guide](https://code.visualstudio.com/api/working-with-extensions/publishing-extension) to package and publish your extension on the Visual Studio Marketplace.

---

## Additional Resources

- [VS Code Extension API Documentation](https://code.visualstudio.com/api)
- [Visual Studio Code Color Theme Guide](https://code.visualstudio.com/api/extension-guides/color-theme)
- [VS Code Extension Quickstart](https://code.visualstudio.com/api/get-started/your-first-extension)

Enjoy building and refining your Arwinux Galaxy theme, and happy coding!
