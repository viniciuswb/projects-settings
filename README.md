# vscode-settings

```
{
  // Define o tema do VSCode
  "workbench.colorTheme": "Dracula",

  // Configura o tamanho e a família da fonte
  "editor.fontSize": 16,
  "editor.lineHeight": 24,
  "editor.fontFamily": "Fira Code",
  "editor.fontLigatures": true,
  "editor.formatOnSave": true,
  "[typescript]": {
    "editor.formatOnSave": false
  },
  "[typescriptreact]": {
    "editor.formatOnSave": false
  },
  "[sql]": {
    "editor.formatOnSave": false
  },

  // Aplica linhas verticais para lembrar de quebrar linha
  // em códigos muito grandes
  "editor.rulers": [80, 120],
  "prettier.eslintIntegration": true,
  "eslint.autoFixOnSave": true,
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    { "language": "typescript", "autoFix": true },
    { "language": "typescriptreact", "autoFix": true }
  ],

  // Aplica um sinal visual na esquerda da linha selecionada
  "editor.renderLineHighlight": "gutter",

  // Aumenta a fonte do terminal
  "terminal.integrated.fontSize": 14,

  // Define o tema dos ícones na sidebar
  "workbench.iconTheme": "material-icon-theme",
  "jetbrainsKeymap.promptV3Features": true,
  "editor.tabSize": 2,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.formatOnPaste": true,
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "typescript.updateImportsOnFileMove.enabled": "never",
  "[javascript]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "explorer.confirmDelete": false,
  "terminal.integrated.rendererType": "dom"
}
```
