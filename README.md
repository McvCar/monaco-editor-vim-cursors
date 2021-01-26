# monaco-editor-vim-cursors

* Editor extension Vim supports multiple cursors

* This code is modified from this base: https://github.com/brijeshb42/monaco-vim

# Usage
```javascript
var editor = monaco.editor.create(document.getElementById('container'), {
  value: ""
  language: 'javascript'
});

let EditorVim = require('editor_vim')
EditorVim.init(editor,monaco);
```
# Finished product preview
Apply to the Cocos Creator built-in editor plug-in: https://forum.cocos.org/t/topic/99871
