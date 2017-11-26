# videoalbum

Videoalbum is a tool that creates a video that can contain multiple songs.

## Installing

```sh
git clone https://github.com/fergusq/videoalbum.git
bilar compress videoalbum
bilar install videoalbum.1.0.0.bil.tar.xz
```

## Usage

```sh
videoalbum <output> { <name> <audio> }
```

For example:

```sh
videoalbum out.mp4 "Happy Xmas" xmas.wav "Last Christmas" lc.wav
```
