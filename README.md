# open-html-in-browser package

HTML files will open in your default browser.

## Features

* HTML files only open.

## Commands

* `open-html-in-browser:open`

## Keymap

No keymap by default.

edit `~/.atom/keymap.cson`

```coffeescript
'atom-text-editor[data-grammar~="html"]':
  'ctrl-shift-q': 'open-html-in-browser:open'
'.tree-view':
  'shift-o': 'open-html-in-browser:selected-entry'
```

## Similar packages

* [open-in-browser](https://atom.io/packages/open-in-browser)
