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
❯ xcpick
1) Xcode-9.4.1.app
2) Xcode-10.1.app
3) Xcode-10.app [CURRENT]
Enter a number to select an Xcode: 2
1) Xcode-9.4.1.app
2) Xcode-10.1.app [CURRENT]
3) Xcode-10.app
```

