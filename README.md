# TetrisCursor

![Preview](https://github.com/jszczerbinsky/TetrisCursor/blob/main/cursor.gif)

# Installation
```shell
git clone https://github.com/jszczerbinsky/TetrisCursor
cd TetrisCursor
mkdir -p tetris/cursors
./generate.sh
mkdir -p ~/.icons
cp -R tetris ~/.icons
```

And add this to your .Xresources

```shell
Xcursor.theme: tetris
```
