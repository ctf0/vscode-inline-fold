# Inline Fold

<p align="center">
    <img width="256" alt="preview" src="https://raw.githubusercontent.com/moalamri/vscode-inline-fold/master/res/icon.png">
</p>

based on https://github.com/moalamri/vscode-inline-fold + changes

## Settings

```jsonc
{
  "inlineFold.regex": "(class|className)=[`'{\"]([^`'\"}]{30,})[`'\"}]",
  "inlineFold.regexFlags": "g",
  "inlineFold.regexGroup": 2,
  "inlineFold.unfoldedOpacity": 0.6,
  "inlineFold.maskChar": "…",
  "inlineFold.maskCss": "color:#000;",
  "inlineFold.supportedLanguages": ["javascriptreact", "typescriptreact"],
  "inlineFold.unfoldOnLineSelect": true,
  "inlineFold.autoFoldOnOpen": true
}
```
