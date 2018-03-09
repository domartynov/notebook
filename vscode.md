# Visual Studio Code Tips

## Config

* Conditional key mapping to switch between terminal and editor, add to `keybindings.json`:
  ```
  { "key": "ctrl+`", "command": "workbench.action.terminal.focus"},
  { "key": "ctrl+`", "command": "workbench.action.focusActiveEditorGroup", "when": "terminalFocus"}
  ```
  
* Sync settings using https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync 
