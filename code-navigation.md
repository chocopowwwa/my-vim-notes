## Foding

`za` - Toggle Fold
`zc` - Close fold
`zo` - Open fold

`zr` - reduces folding by opening one more level of folds throughout the whole buffer
`zR` - to open all folds

`zm` - gives more folding by closing one more level of folds throughout the whole buffer
`zM` - to close all folds

### Fold Method

The 'foldmethod' option (abbreviated to 'fdm') is local to each window. It determines what kind of folding applies in the current window. Possible values are:

- "manual" – folds must be defined by entering commands (such as zf)
- "indent" – groups of lines with the same indent form a fold
- "syntax" – folds are defined by syntax highlighting
- "expr" – folds are defined by a user-defined expression
- "marker" – special characters can be manually or automatically added to your text to flag the start and end of folds
- "diff" – used to fold unchanged text when viewing differences (automatically set in diff mode)

Sources:

- https://vim.fandom.com/wiki/Folding
