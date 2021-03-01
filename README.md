# awesome-codemirror-prosemirror

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

A curated list of awesome CodeMirror 6 & ProseMirror resources

## Intro

CodeMirror 6 and Prosemirror share a few things:

- They're by the same author, [Marijn Haverbeke](https://marijnhaverbeke.nl/)
- They each have their own GitHub Organizations with multiple repos:
  - [CodeMirror](https://github.com/codemirror) ([main repo](https://github.com/codemirror/codemirror.next))
  - [ProseMirror](https://github.com/ProseMirror) ([main repo](https://github.com/ProseMirror/prosemirror))
- It is possible to embed inline and block widgets, and thus one could embed the other
- They each have separate models and views
- Their models allow for undo/redo and custom keybindings
- They rely on HTML5's contenteditable rather than custom rendering, and can work well on mobile
- They're community funded

They also differ in many ways:

- CodeMirror is designed to work primarily with code, and is syntax highlighted
- ProseMirror is designed to work primarily with document trees, like HTML
- CodeMirror 6 is newer than ProseMirror, and written in TypeScript. ProseMirror is older, and written in JavaScript. (ProseMirror is newer than CodeMirror 5 and below.)
- There are more well-known web-based prose editing libraries than there are well-known web-based code-editing libraries
  - Well-known web-based code editing libraries include CodeMirror, Monaco Editor, and ACE Editor
  - Well-known web-based prose (rich text) editing libraries include ProseMirror, CKEditor, Draft.js, Quill, [TinyMCE](https://github.com/tinymce/tinymce), [Substance.js](https://github.com/substance/substance), and [trix](https://github.com/basecamp/trix)
- ProseMirror repos are prefixed with `prosemirror-` while CodeMirror's are unprefixed - with so many repos, it's more work to type the prefix! Repos will sometimes need to be renamed when forking, but it's worth less typing.

This [awesome]((https://awesome.re)) page combines resources for each of them into one
document, to help accelerate learning them both at the same time.

## Integration Libraries

### ProseMirror

- [tiptap](https://github.com/ueberdosis/tiptap) - A renderless rich-text editor for Vue.js

## Official Docs by Category

These are the official docs by category, so the same concepts can be learned with each.
They do share a lot and it's concievable that they could one day be merged into the
same project, but they definitely needed to evolve separately.

CodeMirror is first in these sections, because it's the most popular of the two,
and perhaps the easiest to understand.

### Model

#### CodeMirror

- [codemirror/text](https://codemirror.net/6/docs/ref/#text) ([repo](https://github.com/codemirror/text))
- [codemirror/state](https://codemirror.net/6/docs/ref/#state) ([repo](https://github.com/codemirror/state))

#### ProseMirror

- [prosemirror-model](https://prosemirror.net/docs/ref/#model) ([repo](https://github.com/ProseMirror/prosemirror-model))
- [prosemirror-state](https://prosemirror.net/docs/ref/#state) ([repo](https://github.com/ProseMirror/prosemirror-state))

### Commands, History, and Keybindings

#### CodeMirror

- [commands](https://codemirror.net/6/docs/ref/#commands) ([repo](https://github.com/codemirror/commands))
- [history](https://codemirror.net/6/docs/ref/#history) ([repo](https://github.com/codemirror/history))
- [standardKeymap](https://codemirror.net/6/docs/ref/#commands.standardKeymap) ([code](https://github.com/codemirror/commands/blob/main/src/commands.ts#L691))

#### ProseMirror

- [commands](https://prosemirror.net/docs/guide/#commands)
- [history](https://prosemirror.net/docs/ref/#history)
- [keymap](https://prosemirror.net/docs/ref/#keymap)

## Learning ContentEditable

- [MDN: Making content editable](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Editable_content)
- [MDN: contenteditable global attribute](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/contenteditable)

## Other Editors

### Code

- [CodeMirror 5](https://github.com/codemirror/CodeMirror)
- [Monaco Editor](https://microsoft.github.io/monaco-editor/)
- [Ace](https://ace.c9.io/)
- [Atom](https://github.com/atom)'s [text-editor-component](https://github.com/atom/atom/blob/master/src/text-editor-component.js)

### Prose (Rich Text)

- [CKEditor](https://ckeditor.com/)
- [TinyMCE](https://github.com/tinymce/tinymce)
- [Trix](https://trix-editor.org/)
- [Draft.js](https://draftjs.org/)
- [Quill](https://quilljs.com/)
- [Substance](https://github.com/substance/substance)
- MediaWiki's [VisualEditor](https://www.mediawiki.org/wiki/VisualEditor)
