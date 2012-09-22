#Snippets

The package currently defines the following snippets, which you can use to insert ChordPro formatting elements.
These will be available for `chordpro`,`cho`,`crd`,`chord`,`chopro` files, or when the syntax scope is set to ChordPro.

- `_newsong` start new_song
- `_title` insert/wrap title
- `_subtitle` insert/wrap subtitle
- `_chorus` start/wrap chorus
- `_tab` start a tabulature section
- `_staff` (inserts a 4-bar staff)
- `_c` insert/wrap {comment: xxx}
_ `_ci` insert/wrap {comment_italic: }
- `_def` define new chord-form

#Build

The build system specified will use the include chordii program to compiles the file to a postscript document.
F7 or Tools->Build will output the file into the path where the working file is located.

Currently only for osx and windows. feel free to include the linux binary as well.