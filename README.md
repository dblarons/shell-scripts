# Shell Scripts

Useful scripts for working on the command line. All files in this directory
must be symlinked to `/usr/local/bin`.

## Installation

Symlink all scripts in this repo to `/usr/local/bin`:

`./install`

## Included Scripts

#### agreplace

Use perl and ag to quickly replace all occurrences of a string in a directory.

```
agreplace oldText newText
agreplace "oldText foo" "newText baz"
```
