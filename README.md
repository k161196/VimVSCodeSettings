# VimVSCodeSettings
```
{
"vim.easymotion": true,
  "vim.useCtrlKeys": true,
  "vim.useSystemClipboard": true,
  "vim.digraphs": {},
  //search easy motion to space
  "vim.normalModeKeyBindingsNonRecursive": [
    {
      "before": [" "],
      "after": ["leader", "leader", "leader", "b", "d", "w"]
    }
  ],
  //insert mode
  "vim.insertModeKeyBindings": [
    {
      "before": ["j", "j"],
      "after": ["<Esc>"]
    }
  ], // Visual mode
  "vim.visualModeKeyBindings": [
    // In visual mode i goes to insert mode
    {
      "before": ["i"],
      "after": ["<Esc>", "i"]
    }
  ],
  // Escaping from vim for below commands
  "vim.handleKeys": {
    // Select all
    "<C-a>": false,
    // VS Code search in file
    "<C-f>": false,
    // VS Code new marker @ next occurence
    "<C-d>": false,
    // Copy
    "<C-c>": false,
    // Cut
    "<C-x>": false,
    // Paste
    "<C-v>": false
  }
}
```
