# vscode_my_config

{
    "workbench.startupEditor": "newUntitledFile",
    "editor.renderIndentGuides": false,
    //"workbench.colorTheme": "One Dark Pro",
    "git.enableSmartCommit": true,
    "window.zoomLevel": 0,
    // // Format a file on save. A formatter must be available, the file must not be auto-saved, and editor must not be shutting down.
    "editor.formatOnSave": true,
    // Support using flow through your node_modules folder, WARNING: Checking this box is a security risk. When you open a project we will immediately run code contained within it.
    //"flow.useNPMPackagedFlow": true,
    // Enable/disable JavaScript validation. (For Flow)
    "javascript.validate.enable": false,
    // Enable/disable default JavaScript formatter (For Prettier)
    "javascript.format.enable": false,
    // Use 'prettier-eslint' instead of 'prettier'. Other settings will only be fallbacks in case they could not be inferred from eslint rules.
    "prettier.eslintIntegration": true,
    // "ruby.linter.executablePath": "PathToExecutable",
    // "gitProjectManager.baseProjectsFolders": [
    //     "/home/railsbridge/graphql/best-edusoft-ever",
    //     "/home/railsbridge/best-edusoft-apis"
    // ],
    "indenticator.showHover": true,
    "indenticator.inner.showHighlight": false,
    "workbench.iconTheme": "vscode-icons",
    // "editor.fontFamily": "Fira Code",
    "editor.fontLigatures": true,
    "editor.fontSize": 14,
    "vsicons.dontShowNewVersionMessage": true,
    "sync.gist": "7e736497489e4cf34bce3b9cb7883c2c",
    "sync.host": "",
    "sync.pathPrefix": "",
    "sync.quietSync": false,
    "sync.askGistName": false,
    "sync.removeExtensions": true,
    "sync.syncExtensions": true,
    "sync.autoDownload": false,
    "sync.autoUpload": false,
    "sync.lastUpload": "2018-06-25T02:28:31.774Z",
    "sync.lastDownload": "",
    "sync.forceDownload": false,
    "editor.tabSize": 2,
    "terminal.integrated.rendererType": "dom",
    // Basic settings: turn linter(s) on
    "ruby.lint": {
        "reek": false,
        "rubocop": true,
        "ruby": false, //Runs ruby -wc
        "fasterer": false,
        "debride": false,
        "ruby-lint": false
    },
    // Time (ms) to wait after keypress before running enabled linters. Ensures
    // linters are only run when typing has finished and not for every keypress
    "ruby.lintDebounceTime": 500,
    //advanced: set command line options for some linters:
}
