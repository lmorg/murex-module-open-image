# open-image

This _murex_ module creates a data type for images (`image`) and creates an
open handler which renders those images in the terminal.

It also creates a `config` option to select which terminal rendering method to
use, however it defaults to "auto" where _murex_ will attempt to auto-detect
the best method supported by your terminal emulator.
