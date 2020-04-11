# Command-line Zettelkasten for arbitrary document types

For auto-completion, add this to dotspacemacs/user-config:
```
  (setq tags-add-tables t)
  (setq tags-table-list
        '("~/.emacs.d/zettel-TAGS"))
  )
```


## Usage:

- Create a new note using the `tex` template:
`./new note-name tex`.
- Write notes into `notes/note-name/note.tex`.
- Add topics and links to other notes in `notes/note-name/metadata`. `complete-tag` can be used to auto-complete the links and existing topic names.
- Run `./compile` to update topics and links.

## TODO

- Command line tool to see notes in a particular topic, or linked to a particular note.
- Easy way to view these notes.
