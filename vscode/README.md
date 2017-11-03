# VSCode

## User Settings

```json
{
  "workbench.iconTheme": "vscode-icons",
  "workbench.colorTheme": "One Dark Pro",
  "editor.tabSize": 2,
  "editor.rulers": [120],
  "editor.wordWrap": "wordWrapColumn",
  "editor.wordWrapColumn": 120,
  "editor.formatOnSave": true,
  "vsicons.dontShowNewVersionMessage": true,
  "eslint.autoFixOnSave": true,
  "prettier.eslintIntegration": true,
  "workbench.startupEditor": "none",
  "editor.snippetSuggestions": "top",
  "editor.tabCompletion": true
}
```

## Keybord Shortcuts (Ubuntu)

| `keybindings.ubuntu.json`

| key | description | command |
|-----|-------------|---------|
| `A` | Create new file in focused directory | `explorer.newFile` |
| `Shift + A` | Create new folder in focused directory | `explorer.newFolder` |
| `Alt + →` | Jump to end of line | `cursorEnd` |
| `Shift + Alt + →` | Jump to end of line and select | `cursorEndSelect` |
| `Alt + ←` | Jump to start of line | `cursorHome` |
| `Shift + Alt + ←` | Jump to start of line and select | `cursorHomeSelect` |

## Plugins

- [vscode-icons](https://marketplace.visualstudio.com/items?itemName=robertohuertasm.vscode-icons) - icon theme
- [One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme) - dark color theme
- [Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager) - project manager
  - `Shift + Alt + P` - to list projects
- [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) - EditorConfig support
- [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight) - highlights color in code
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) - path import suggestions
- [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) - import suggestions based on `package.json`
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) - ESlint support
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) - rename tag plugin
- [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag) - close tag plugin
- [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) - markdown linting/errors info
- [Reactjs code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.ReactSnippets) - PropTypes & other shortcuts
- [vscode-styled-components](https://marketplace.visualstudio.com/items?itemName=jpoissonnier.vscode-styled-components) - styled-components css syntax highlight

## Snippets

- `snippets.javascript.json`:
  - `log` - console.log

### EditorConfig

| `.editorconfig`
