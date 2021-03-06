# Notepas
A portable multi-platform text editor with a small footprint.

This is the place where new [builds](https://github.com/beNative/Notepas/releases) will be released. 

The sources are maintained on [this location](http://github.com/beNative/lazarus), together with all dependencies needed to make a new build.

# Introduction

Notepas is a fast portable native multiplatform text editor written in Lazarus and can be compiled for multiple platforms and widget sets using the advanced native Free Pascal Compiler. Aimed towards developers it is equipped with some functions usually not found in other text editors and introduces a couple of new exclusive features:

* **Alpha blended coloring** supporting multiple layers of transparency for both text and background.
* **Code filter**: a tool to filter lines that match a given search string or regular expression.
* **Code shaper**: a set of tools to apply advanced formatting rules to a text selection.
* **Smart select**: make (customizable) selections that depend on the active highlighter and context.
* **Align lines**: align multiple lines based on tokens found in the current selection.
* **Common Syntax coloring rules** for all registered highlighters.
* **Advanced docking** support.

# Main features

## Code filter

![Notepas](https://github.com/beNative/lazarus/blob/master/projects/notepas/images/Notepas.CodeFilter.png)

## Multi-caret editing

![Notepas](https://github.com/beNative/lazarus/blob/master/projects/notepas/images/Notepas.MultiCaret.png)

## Synchronized editing

![Notepas](https://github.com/beNative/lazarus/blob/master/projects/notepas/images/Notepas.SyncEdit.png)

## Align selection

![Notepas](https://github.com/beNative/lazarus/blob/master/projects/notepas/images/Notepas.AlignSelection.png)

## Docking

![Notepas](https://github.com/beNative/lazarus/blob/master/projects/notepas/images/Notepas.DockingViews.png)

## Search

![Notepas](https://github.com/beNative/lazarus/blob/master/projects/notepas/images/Notepas.FindInAllViews.png)

# Other features:

* Single native and fast executable, no external libraries required.
* Portable, as settings are stored in a single XML-file.
* Syntax highlighting.
* Code folding depending on syntax (currently for XML, HTML and Pascal code but will be extended to support other highlighters).
* Multi-line comment folding.
* Selection folding.
* Region folding.
* Line modification indicators.
* Line numbers display.
* Smart searching of the word at the caret position (CTRL-ALT-UP/CTRL-ALT-DOWN)
* Highlighting of words matching the selected word.
* Highlighting of text matching the selected block.
* Highlighting of matching bracket.
* Routine seperators.
* Highlighting of search matches.
* Comment and uncomment (for both line and block comments) handling depending on active highlighter.
* Column selection mode.
* Supports user definable highlighters. Highlighter rules can be specified using XML.
* Extensive set of keyboard shortcuts allowing fast navigation and intuitive text editing.
* Drag and drop support for both files and code selections.
* Search & replace in multiple opened files with regular expression support.
* Support for multiple encoding schemes (Unicode and many others).
* Support for multiple line endings (Windows, Unix, Mac).
* Zoom.
* Localization support using simple text files that are loaded by the application at runtime (i18n using GetText).
* Monitor external changes.

## Planned features

* Bookmark support.
* Support for both internal and external code formatters.
* Support for Pascal/Python scripting.
* Hex editor.
* HTML viewer.
* Structure viewer.
* Support for multiple views on the same source buffer.
* Support for keyboard macros.

A lot of other unique features will be added soon so stay tuned as the code evolves. For now only preview builds for the Windows, Linux and MacOS X (Darwin) platforms are available, but native FreeBSD and Solaris builds are in the pipeline.

Notepas is a work-in-progress. If you have bug reports or suggestions for new features please submit a new issue.  Experimental features are activated in debug mode and provide a preliminary look to what's currently cooking in the kitchen.
