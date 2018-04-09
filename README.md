# vscode-configs

{
  "python.linting.pylintArgs": [
    "--disable=C0111",
    "--disable=C0103"
  ],
  "window.zoomLevel": -2,
  "editor.tabSize": 2,
  "typescript.check.npmIsInstalled": false,
  "editor.minimap.enabled": false,
  "vsicons.projectDetection.autoReload": true,
  "editor.fontFamily": "'Fixedsys Excelsior 3.01' inconsolata",
  "editor.fontSize": 28,
  "editor.lineHeight": 32,
  "editor.fontLigatures": true,
  "terminal.integrated.fontSize": 16,
  "terminal.integrated.fontFamily": "inconsolata",
  "git.enableSmartCommit": true,
  "git.confirmSync": false,
  "workbench.colorTheme": "Monokai Pro (Filter Spectrum)",
  "emmet.syntaxProfiles": {
    "javascript": "jsx",
    "xml": {
      "attr_quotes": "single"
    }
  },
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "emmet.triggerExpansionOnTab": true,
  "explorer.confirmDragAndDrop": false,
  "files.exclude": {
    "**/.git": true, // this is a default value
    "**/.DS_Store": true, // this is a default value
    "**/node_modules": true, // this excludes all folders 
    "**/package-lock.json": true,
    "node_modules": true // this excludes the folder 
  },
  "git.autofetch": true,
}
