# BookmarkBeacon

##### VSCODE EXTENSION

<p align="center">
<img src="https://raw.githubusercontent.com/bluecaret/BookmarkBeacon/master/images/logo.png" width="320px" />
</p>

Forked from: [line_highlight_bookmark_vscode](https://github.com/balmacefa/line_highlight_bookmark_vscode) (which in turn was forked from: [vscode-bookmarksng](https://github.com/chestozo/vscode-bookmarksng))

Install:

Bookmark with highlight lines, icon, and overview ruler highlight.

<p align="center">
<img src="https://raw.githubusercontent.com/bluecaret/BookmarkBeacon/master/images/example.gif" width="550px" />
</p>

## Shortcuts

These shortcuts can be modified in Settings:

- `Cmd+M` (`Ctrl+M`) — toggle bookmarks (multi-cursor supported).

  > Reference: bookmarkbeacon.toogleBookmarks

- `Cmd+Shift+M` (`Ctrl+Shift+M`) — clear all bookmarks in current file

  > Reference: bookmarkbeacon.clearAllBookmarks

- `F2` — move cursor to the next bookmarked line of code (cursor is moved at the end of the line)
  > Reference: bookmarkbeacon.navigateToNextBookmark
- `F2+Shift` — move cursor to the previous bookmarked line of code (cursor is moved at the end of the line)
  > bookmarkbeacon.navigateToPrevBookmark

## Properties

These properties can be modified in Settings:

- `alignTopOnNavigation` — If set bookmarked line will become the topmost when using next / previous navigation commands. `default: false`

  > bookmarkbeacon.alignTopOnNavigation

- `display` — Sets how the bookmark is displayed. Can choose between showing a line in the editor and overview ruler (`'line'`), an icon in the gutter (`'icon'`), or both. (default: `'both'`)

  > bookmarkbeacon.display

- `icon` — Choose which style of icon to show in the gutter. Options: `'icon'`, `'icon-color'`, `'logo'`, `'logo-color'`. (default: `'icon'`)

  > bookmarkbeacon.icon

- `lineColor` — Change the line color. (e.g. `'red'`, `'#FFF'` `'#FFFFFFF'`, `'RGB(255,255,255)'`,`'RGB(255, 255, 255. 0.5)'`) (default: `'#00FFFF'`)

  > bookmarkbeacon.lineColor

- `lineWidth` — Change the line width (default: `3`)

  > bookmarkbeacon.lineWidth

- `lineStyle` — Change the line style. Options: `'solid'`, `'dashed'`, `'inset'`, `'double'`, `'groove'`, `'outset'`, `'ridge'` (default: `'solid'`)

  > bookmarkbeacon.lineStyle

## Features

- Line renderer highlight the entire line for quick visual reference

- **multi-cursor supported!** — add multiple bookmarks with a single shortcut / command run

- **multi-editor supported!** — Line highlight stays always on

- bookmarks are set for lines (not for selection ranges)

- context dependent bookmarks toggle

- for single cursor mode - normal bookmark toggle is performed

- for multi-cursor - bookmarks are set if there is at least one line without a bookmark. Otherwise bookmarks are unset

- remove bookmarks inside multi-line selection on bookmark toggle. Works only for single multi-line selection

- navigation to next / previous bookmark with a shortcut

## Thank you!

Modified from [line_highlight_bookmark_vscode](https://github.com/balmacefa/line_highlight_bookmark_vscode).

**Modifications made by [BlueCaret](https://github.com/bluecaret).**

[Buy me a coffee](https://buymeacoffee.com/bluecaret)
