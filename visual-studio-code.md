## Visual Studio Code

File ➔ Preferences ➔ Keyboard Shortcuts

```json
[
    { "key": "alt+j",                
      "command": "editor.action.addSelectionToNextFindMatch",
      "when": "editorFocus" },
    { "key": "ctrl+d",   
      "command": "editor.action.copyLinesDownAction",
      "when": "editorTextFocus" },
    { "key": "ctrl+w",
      "command": "editor.action.smartSelect.grow",
      "when": "editorTextFocus" },
    { "key": "ctrl+shift+w",
      "command": "editor.action.smartSelect.shrink",
      "when": "editorTextFocus" }
]
```
