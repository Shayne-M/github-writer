## GitHub WYSIWYG Rich-Text Editor

Replaces the plain-text markdown input textareas from GitHub.com pages with a
WYSIWYG rich-text editor, powered by [CKEditor](https://ckeditor.com/).

### Features

One of the goals of this extension is providing all features which are available in the GitHub plain-text editor, including all markdown features. The following is the list of GitHub features, with the ones checked already available in the GitHub RTE:

*   Inline formatting
    *   [x] Bold
    *   [x] Italic
    *   [x] Strikethrough
    *   [x] Inline code
*   Structure
    *   [x] Paragraphs (Enter)
    *   [x] Soft line-break (Shift+Enter)
    *   [x] Headings
    *   [x] Horizontal line separator
*   Blocks
    *   [x] Quote
        *   [ ] Quote in quote (levels)
    *   [x] Code block
        *   [ ] Language selection
*   Lists
    *   [x] Bulleted list
    *   [x] Numbered list
    *   [x] Task/Todo list
*   Links
    *   [x] On text
    *   [ ] On images
    *   [x] Auto-link URLs on pasting.
    *   [ ] Auto-link URLs on typing.
*   Media
    *   [x] Images
        *   [x] Drag-and-drop
        *   [x] Paste
        *   [x] Open file dialog
    *   [ ] Files
        *   [ ] Drag-and-drop
        *   [ ] Open file dialog
*   Auto-complete
    *   [x] People (list when typing "@")
    *   [x] Issues/PRs (list when typing "#")
*   Other
    *   [x] Emoji
        *   [x] OS, Unicode characters
        *   [x] Auto-complete (list when typing ":")
    *   [x] Escape markdown in text
    *   [x] Tables
    *   [ ] Saved replies
    *   [ ] Load quoted text ("r" key)

### Pages enabled

The GitHub RTE should be enabled in all places where the original markdown editor is available. The following is the current status of the implementation:

*   [x] Issues
    *   [x] New
    *   [x] Editing
    *   [x] Comment
        *   [x] Editing
*   [ ] Pull requests
    *   [ ] Comment
        *   [ ] Editing
*   [ ] Commits
    *   [ ] Comment
    *   [ ] Line comment
*   [ ] Settings > Saved replies
*   [ ] Wiki pages (well, that's s whole different editor, still a target)
---

Copyright (c) 2003-2019, [CKSource](https://cksource.com/) Frederico Knabben.
All rights reserved.
