# User Settings

```
{
    "editor.tabSize": 2,
    "editor.rulers": [140]
}
```

# Keybord Shortcuts

- `explorer.newFile` - create new file in focused directory (`A`)
- `explorer.newFolder` - create new folder in focused directory (`Shift + A`)

```
[
  {
    "key": "a",
    "command": "explorer.newFile",
    "when": "!editorFocus"
  },
  {
    "key": "shift+a",
    "command": "explorer.newFolder",
    "when": "!editorFocus"
  }
]
```

# Plugins