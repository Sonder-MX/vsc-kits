# Python Kits

## Introduce

VS Code Python Application Development Extension Pack.

## Recommended Configuration

- Workspace Settings

```json
{
    "python.languageServer": "Pylance",
    "python.analysis.completeFunctionParens": true,

    // "python.envFile": "/path/.env",
    // "python.defaultInterpreterPath": "/path/.env/Scripts/python.exe",

    "[python]": {
      "editor.defaultFormatter": "ms-python.black-formatter",
      "editor.formatOnSave": true,
      "editor.codeActionsOnSave": {
        "source.organizeImports": "explicit"
      }
    },
    "black-formatter.args": [
      "--line-length",
      "120"
    ],
    "isort.args": [
      "--profile",
      "black"
    ]
}
```
