# Change Log

## 0.0.1

- Initial release

## 0.0.2

- add option to clear decorations on save

## 0.0.3

- change how we check for document content changes to become like the editor's "don't save document content on save, rather on open only"

## 0.0.4

- extra configs

## 0.0.5

- fix not correctly reseting cached files

## 0.0.7

- fix trying to get content on file close

## 0.0.9

- fix package settings name

## 0.1.0

- remove comments reply box
    - disable comments for now as its giving error
- better api (using `git diff`)
- add new key **change** to `miniDiff.styles` to show edited/changed lines
- now instead of having a comment per line, it will be a comment per group of consecutive lines, more performant & wont slow/kill the editor
- correct display of changed lines
- update LICENSE
- update rdme
- add new config `miniDiff.debounceTime`
- add new config `miniDiff.showDiffOutput`
- add new config `miniDiff.gitPath`

## 0.1.1

- fix not working after save

## 0.1.2

- add new config `miniDiff.schemeTypes`

## 0.1.3

- add new config `miniDiff.terminalShellPath` thanks to [pit00](https://github.com/pit00)

## 0.1.4

- add cmnds to navigate the changes made like git thanks to [pit00](https://github.com/pit00) for suggestion

## 0.1.5

- fix gutter color customization at Windows
- add new config `miniDiff.gitDisable`
- add new config for overview styles: position (can be "Center", "Left", "Right" or "Full")
