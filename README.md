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
