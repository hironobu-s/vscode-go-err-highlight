# go-err-highlighting

## Features

This extension highlights the error variables such as `err` and `errCh` in your Go source code.

   
|![before.png](before.png)|![after.png](after.png)|
|---|---|
|Before|After|

## Extension Settings

You can define the highlight color of the error variables by adding editor.tokenColorCustomizations section to your `settings.js`.
`
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": "keyword.err.go",
        "settings": {
          "foreground": "#DD3D05",
          "fontStyle": "bold",
        }
      }
    ]
  }
``
Calling out known issues can help limit users opening duplicate issues against your extension.

## Release Notes


### 0.0.1

Initial release
