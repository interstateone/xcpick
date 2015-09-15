# xcpick

I made this, based on [xcode-toggle](https://github.com/schwa/xcode-toggle) by [@schwa](https://twitter.com/schwa), because I wanted to see if it could be done in Bash as a little learning exercise. Contributions welcome, but it's just a little thing I made for myself, so it should stay small. If you get something out if it, that's awesome too :smile:.

## Installation

Put xcpick somewhere in your PATH. I've got it in `~/bin`.

```
git clone git@github.com:interstateone/xcpick.git && cd xcpick
ln -s $PWD/xcpick ~/bin/xcpick
```

## Usage

```
❯ xcpick -h
Usage: xcpick [COMMAND]

Commands:
  print       Prints the currently selected Xcode path.
  list        Lists all Xcodes in /Applications.
  toggle      Cycles through all Xcodes in /Applications.
  pick        Lists all Xcodes and waits for a selection to be made.
  set [PATH]  Select a Xcode at a path.
  -h, --help  Show this message.
```

