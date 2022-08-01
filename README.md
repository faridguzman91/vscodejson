# vscodejson
my custom settings for vscode

{
    "[html]": {
        "editor.defaultFormatter": "vscode.html-language-features"
    },
    "[css]": {
        "editor.defaultFormatter": "aeschli.vscode-css-formatter"
    },
    "vsicons.dontShowNewVersionMessage": true,
    "[javascript]": {
        "editor.defaultFormatter": "HookyQR.beautify"
    },
    "yaml.schemas": {
        "file:///Users/faridguzman/.vscode/extensions/atlassian.atlascode-2.10.12/resources/schemas/pipelines-schema.json": "bitbucket-pipelines.yml"
    },
    "atlascode.configurationTarget": "workspace",
    "atlascode.jira.jqlList": [
        {
            "id": "0650b1f6-7e4e-4e14-882e-9e025c8bfca5",
            "enabled": true,
            "name": "My jira.creapolis.nl Issues",
            "query": "assignee = currentUser() AND resolution = Unresolved ORDER BY lastViewed DESC",
            "siteId": "jira.creapolis.nl",
            "monitor": true
        }
    ],
    "diffEditor.ignoreTrimWhitespace": false,
    "editor.renderControlCharacters": true,
    "terminal.integrated.allowMnemonics": true,
    "explorer.confirmDragAndDrop": false,
    "explorer.confirmDelete": false,
    "editor.defaultFormatter": "HookyQR.beautify",
    "editor.fontSize": 13,
    "editor.formatOnPaste:" : true,
    "editor.formatOnSave" : true,
    "editor.fontFamily" : "FuraMono Nerd Font",
    "workbench.editor.highlightModifiedTabs" : true,
    "files.autoSaveDelay": "afterDelay",
    "explorer.sortOrder": "type",
    "editor.cursorBlinking": "smooth",
    "editor.acceptSuggestionOnEnter" : "off",
    "editor.fontLigatures": true,
    "diffEditor.codeLens": true,
    "diffEditor.wordWrap": "on",
    "redhat.telemetry.enabled": false,
    "workbench.colorTheme": "Andromeda",
    "git.autofetch": true,
    "[javascriptreact]": {
        "editor.defaultFormatter": "vscode.typescript-language-features"
    },
    "javascript.updateImportsOnFileMove.enabled": "always",
    "editor.wordWrap": "on",
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true,
        "source.fixAll": true,
        "source.sortImports": true,
    },
    "security.workspace.trust.untrustedFiles": "open",
    "files.autoSave": "afterDelay",
    "git.suggestSmartCommit": false,
    "editor.inlineSuggest.enabled": true,
    "window.zoomLevel": -1,
    "[typescriptreact]": {
        "editor.defaultFormatter": "vscode.typescript-language-features"
    },
    "tabnine.experimentalAutoImports": true
}
