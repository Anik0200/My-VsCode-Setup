```json

{
  "files.autoSave": "afterDelay",
  "[php]": {
    "editor.defaultFormatter": "kokororin.vscode-phpfmt"
  },

  "editor.minimap.enabled": false,
  "code-runner.executorMap": {
    "javascript": "node",
    "java": "cd $dir && javac $fileName && java $fileNameWithoutExt",
    "c": "cd $dir && gcc $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
    "zig": "zig run",
    "cpp": "cd $dir && g++ $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
    "objective-c": "cd $dir && gcc -framework Cocoa $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
    "php": "C:\\laragon\\bin\\php\\php-8.3.12-Win32-vs16-x64\\php.exe",
    "python": "python -u",
    "perl": "perl",
    "perl6": "perl6",
    "ruby": "ruby",
    "go": "go run",
    "lua": "lua",
    "groovy": "groovy",
    "powershell": "powershell -ExecutionPolicy ByPass -File",
    "bat": "cmd /c",
    "shellscript": "bash",
    "fsharp": "fsi",
    "csharp": "scriptcs",
    "vbscript": "cscript //Nologo",
    "typescript": "ts-node",
    "coffeescript": "coffee",
    "scala": "scala",
    "swift": "swift",
    "julia": "julia",
    "crystal": "crystal",
    "ocaml": "ocaml",
    "r": "Rscript",
    "applescript": "osascript",
    "clojure": "lein exec",
    "haxe": "haxe --cwd $dirWithoutTrailingSlash --run $fileNameWithoutExt",
    "rust": "cd $dir && rustc $fileName && $dir$fileNameWithoutExt",
    "racket": "racket",
    "scheme": "csi -script",
    "ahk": "autohotkey",
    "autoit": "autoit3",
    "dart": "dart",
    "pascal": "cd $dir && fpc $fileName && $dir$fileNameWithoutExt",
    "d": "cd $dir && dmd $fileName && $dir$fileNameWithoutExt",
    "haskell": "runghc",
    "nim": "nim compile --verbosity:0 --hints:off --run",
    "lisp": "sbcl --script",
    "kit": "kitc --run",
    "v": "v run",
    "sass": "sass --style expanded",
    "scss": "scss --style expanded",
    "less": "cd $dir && lessc $fileName $fileNameWithoutExt.css",
    "FortranFreeForm": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
    "fortran-modern": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
    "fortran_fixed-form": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
    "fortran": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
    "sml": "cd $dir && sml $fileName",
    "mojo": "mojo run",
    "erlang": "escript",
    "spwn": "spwn build",
    "pkl": "cd $dir && pkl eval -f yaml $fileName -o $fileNameWithoutExt.yaml",
    "gleam": "gleam run -m $fileNameWithoutExt"
  },
  "code-runner.executorMapByFileExtension": {
    ".vb": "cd $dir && vbc /nologo $fileName && $dir$fileNameWithoutExt",
    ".vbs": "cscript //Nologo",
    ".scala": "scala",
    ".jl": "julia",
    ".cr": "crystal",
    ".ml": "ocaml",
    ".zig": "zig run",
    ".exs": "elixir",
    ".hx": "haxe --cwd $dirWithoutTrailingSlash --run $fileNameWithoutExt",
    ".rkt": "racket",
    ".scm": "csi -script",
    ".ahk": "autohotkey",
    ".au3": "autoit3",
    ".kt": "cd $dir && kotlinc $fileName -include-runtime -d $fileNameWithoutExt.jar && java -jar $fileNameWithoutExt.jar",
    ".kts": "kotlinc -script",
    ".dart": "dart",
    ".pas": "cd $dir && fpc $fileName && $dir$fileNameWithoutExt",
    ".pp": "cd $dir && fpc $fileName && $dir$fileNameWithoutExt",
    ".d": "cd $dir && dmd $fileName && $dir$fileNameWithoutExt",
    ".hs": "runhaskell",
    ".nim": "nim compile --verbosity:0 --hints:off --run",
    ".csproj": "dotnet run --project",
    ".fsproj": "dotnet run --project",
    ".lisp": "sbcl --script",
    ".kit": "kitc --run",
    ".v": "v run",
    ".vsh": "v run",
    ".sass": "sass --style expanded",
    ".cu": "cd $dir && nvcc $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
    ".ring": "ring",
    ".sml": "cd $dir && sml $fileName",
    ".mojo": "mojo run",
    ".erl": "escript",
    ".spwn": "spwn build",
    ".pkl": "cd $dir && pkl eval -f yaml $fileName -o $fileNameWithoutExt.yaml",
    ".gleam": "gleam run -m $fileNameWithoutExt"
  },
  "editor.stickyScroll.enabled": false,
  "codeium.enableCodeLens": false,
  "security.workspace.trust.untrustedFiles": "open",
  "security.promptForLocalFileProtocolHandling": false,
  "terminal.integrated.altClickMovesCursor": false,
  "workbench.settings.applyToAllProfiles": ["FiraCode-Retina"],

  "workbench.iconTheme": "material-icon-theme",
  "liveServer.settings.donotShowInfoMsg": true,
  "codeium.enableConfig": {
    "*": true,
    "plaintext": true
  },
  "[javascript]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },
  "editor.formatOnSave": true,
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "workbench.colorTheme": "Ayu Dark",
  "reactSnippets.settings.prettierEnabled": true,
  "prettier.endOfLine": "auto",
  "prettier.printWidth": 150,
  "phpfmt.enable_auto_align": true,
  "terminal.explorerKind": "both",
  "terminal.external.linuxExec": "bash",
  "terminal.external.windowsExec": "C:\\Program Files\\Git\\git-bash.exe",
  "terminal.integrated.defaultProfile.windows": "Git Bash",
  "prettier.ignorePath": ".pi",
  "javascript.updateImportsOnFileMove.enabled": "always",
  "workbench.statusBar.visible": false,

  /////////////Setting One
  "editor.copyWithSyntaxHighlighting": false,
  "diffEditor.ignoreTrimWhitespace": false,
  "editor.emptySelectionClipboard": false,
  "workbench.editor.enablePreview": false,
  "window.newWindowDimensions": "inherit",
  "editor.multiCursorModifier": "ctrlCmd",
  "files.trimTrailingWhitespace": true,
  "diffEditor.renderSideBySide": false,
  "editor.snippetSuggestions": "top",
  "editor.detectIndentation": false,
  "window.nativeFullScreen": true,
  "files.insertFinalNewline": true,
  "files.trimFinalNewlines": true,
  "editor.lineNumbers": "off",
  "editor.guides.indentation": false,
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  // Silence the Noise
  "breadcrumbs.enabled": false,
  "scm.diffDecorations": "none",
  "editor.hover.enabled": true,
  "editor.matchBrackets": "never",
  "workbench.tips.enabled": false,

  "git.decorations.enabled": false,
  "workbench.startupEditor": "none",
  "editor.lightbulb.enabled": "off",
  "editor.selectionHighlight": false,
  "editor.overviewRulerBorder": false,
  "editor.renderLineHighlight": "none",
  "editor.occurrencesHighlight": "off",
  "problems.decorations.enabled": false,
  "editor.renderControlCharacters": false,
  "editor.hideCursorInOverviewRuler": true,
  "editor.gotoLocation.multipleReferences": "goto",
  "editor.gotoLocation.multipleDefinitions": "goto",
  "editor.gotoLocation.multipleDeclarations": "goto",
  "editor.gotoLocation.multipleImplementations": "goto",
  "editor.gotoLocation.multipleTypeDefinitions": "goto",
  "workbench.editor.enablePreviewFromQuickOpen": false,
  "workbench.activityBar.location": "hidden",

  // Typography
  "editor.fontFamily": "JetBrains Mono",
  "editor.fontLigatures": true,
  "editor.suggestFontSize": 16,
  "editor.suggestLineHeight": 30,
  "terminal.integrated.lineHeight": 1.5,
  "terminal.integrated.fontSize": 16,

  "search.useIgnoreFiles": false,
  "search.exclude": {
    // Hide everything in /vendor, except the "laravel" and "livewire" folder.
    "**/vendor/{[^l],?[^ai]}*": true,
    // Hide everything in /public, except "index.php"
    "**/public/{[^i],?[^n]}*": true,
    "**/node_modules": true,
    "**/dist": true,
    "**/_ide_helper.php": true,
    "**/composer.lock": true,
    "**/package-lock.json": true,
    "storage": true,
    ".phpunit.result.cache": true
  },

  // Include "-" in word selection.
  "emmet.includeLanguages": {
    "blade": "html",
    "vue-html": "html",
    "vue": "html",
    "react": "html",
    "javascript": "html"
  },
  "files.associations": {
    ".php_cs": "php",
    ".php_cs.dist": "php"
  },

  // PHP
  "php.suggest.basic": false,
  "workbench.tree.enableStickyScroll": false,

  //Custom Css
  "vscode_custom_css.imports": [
     "file:///C:/Users/Administrator/.vscode/assets/script.js",
     "file:///C:/Users/Administrator/.vscode/assets/style.css"
  ],
  "window.menuBarVisibility": "compact",
  "editor.wordWrap": "on",
  "[json]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "auto-close-tag.activationOnLanguage": [
    "xml",
    "php",
    "blade",
    "ejs",
    "jinja",
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact",
    "plaintext",
    "markdown",
    "vue",
    "liquid",
    "erb",
    "lang-cfml",
    "cfml",
    "HTML (EEx)",
    "HTML (Eex)",
    "plist"
  ]
}
```
