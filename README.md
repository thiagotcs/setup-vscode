# setup-vscode
{
  "tabnine.experimentalAutoImports": true,
    "workbench.colorTheme": "Dracula",
    "editor.minimap.enabled": false,
    "workbench.sideBar.location": "right",
    
    "editor.semanticHighlighting.enabled": false,
    "editor.fontFamily": "JetBrains Mono",
    "editor.fontLigatures": true,
    "editor.lineHeight": 26,
    "editor.fontSize": 16,
    "editor.tabSize": 2,
    
    "terminal.integrated.defaultProfile.linux": "zsh",
    "terminal.integrated.fontSize": 14,
    "workbench.iconTheme": "material-icon-theme",
    "workbench.startupEditor": "newUntitledFile",
    "polacode.backgroundColor": "#61dafb",
    
    "explorer.compactFolders": false,
    "editor.renderLineHighlight": "gutter",
    "workbench.editor.labelFormat": "short",
    "extensions.ignoreRecommendations": true,
  
    "breadcrumbs.enabled": true,
    "editor.parameterHints.enabled": false,
    "explorer.confirmDragAndDrop": false,
    "explorer.confirmDelete": false,
    
    "editor.rulers": [80, 120],
    "editor.formatOnSave": false,
    "editor.codeActionsOnSave": {
      "source.fixAll.eslint": true
    },
    
    "files.exclude": {
      "**/.git": true,
      "**/.svn": true,
      "**/.hg": true,
      "**/CVS": true,
      "**/.DS_Store": true,
      // "**/node_modules": true
    },

    "[prisma]": {
      "editor.formatOnSave": true
    },
  
    "files.associations": {
      ".sequelizerc": "javascript",
      ".stylelintrc": "json",
      ".prettierrc": "json",
      "*.tsx": "typescriptreact",
      ".env.*": "dotenv"
    },
  
    "emmet.syntaxProfiles": { "javascript": "jsx" },
    "emmet.includeLanguages": { "javascript": "javascriptreact" },
    
    "gitlens.codeLens.recentChange.enabled": false,
    "gitlens.codeLens.authors.enabled": false,
    "gitlens.codeLens.enabled": false,
  
    "git.enableSmartCommit": true,
    "liveshare.featureSet": "insiders", 

    "typescript.tsserver.log": "off",
    "javascript.suggest.autoImports": true,
    "typescript.suggest.autoImports": true,
    "material-icon-theme.activeIconPack": "nest",
    "screencastMode.onlyKeyboardShortcuts": true,

    "material-icon-theme.folders.associations": {
        "infra": "app",
        "entities": "class",
        "domain": "class",
        "schemas": "class",
        "typeorm": "database",
        "repositories": "mappings",
        "http": "container",
        "migrations": "tools",
        "modules": "components",
        "implementations": "core",
        "dtos": "typescript",
        "fakes": "mock",
        "websockets": "pipe",
        "protos": "pipe",
        "grpc": "pipe",
        "providers": "include",
        "subscribers": "messages",
        "useCases": "controller",
        "kafka": "scripts",
        "mappers": "meta",
        "_shared": "shared",
        "eslint-config": "tools",
        "kube": "kubernetes"
    },

    "material-icon-theme.files.associations": {
        "ormconfig.json": "database",
        "tsconfig.json": "tune",
        "*.proto": "3d",
        "*.webpack.js": "webpack"
    },

    "material-icon-theme.languages.associations": {
        "dotenv": "tune"
    },
  
    "window.menuBarVisibility": "toggle",
    "typescript.updateImportsOnFileMove.enabled": "never",
    "cSpell.enableFiletypes": [
        "!asciidoc",
        "!c",
        "!cpp",
        "!csharp",
        "!go",
        "!handlebars",
        "!haskell",
        "!jade",
        "!java",
        "!latex",
        "!php",
        "!pug",
        "!python",
        "!restructuredtext",
        "!rust",
        "!scala",
        "!scss"
    ],
    "cSpell.language": "en,pt",
    "editor.suggestSelection": "first",
    "codesnap.backgroundColor": "transparent",
    "codesnap.transparentBackground": true,
    "codesnap.boxShadow": "0 0 0",
    "liveServer.settings.donotVerifyTags": true,
    "cSpell.userWords": [
      "chakra",
      "middlewares",
      "prefetch",
      "rocketseat",
      "upsert"
    ],
    "javascript.updateImportsOnFileMove.enabled": "always",
    "terminal.integrated.showExitAlert": false,

    "splitHTMLAttributes.closingBracketOnNewLine": true,
    "todo-tree.general.tags": [
      "BUG",
      "HACK",
      "FIXME",
      "TODO",
      "XXX",
      "[ ]",
      "[x]"
    ],
    "todo-tree.regex.regex": "(//|#|<!--|;|/\\*|^|^\\s*(-|\\d+.))\\s*($TAGS)",
    "security.workspace.trust.untrustedFiles": "newWindow",
    "window.zoomLevel": 0,
    "terminal.integrated.tabs.enabled": false,
    "window.title": "${dirty}${activeEditorShort}${separator}${rootPath}${rootName}${separator}${appName}",
    "workbench.productIconTheme": "fluent-icons",
    "window.titleBarStyle": "custom"

}
