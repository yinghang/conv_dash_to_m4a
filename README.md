# Convert Dash to m4a using FFMPEG

First install ffmpeg
```
brew install ffmpeg
```

then convert your youtube-dl dash file to m4a
```
ffmpeg -i input.m4a -vn -c:a copy output.m4a
```
