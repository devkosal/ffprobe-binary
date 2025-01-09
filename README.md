# ffprobe-binary
lightweight binaries for ffprobe


`ffrpobe` is a very useful tool but usually comes packaged with `ffmpeg`. 

You can download standalone binaries for `ffprobe` here: [https://ffbinaries.com/downloads](https://ffbinaries.com/downloads)

However the size of even these `ffprobe` binaries is north of 70 mb after unzipping. This isn't ideal for limited resource environments.

This repo hosts compressed versions of these binaries using upx e.g. `upx --best --lzma ffprobe`

This reduces the size considerably i.e. from 78 mb -> 20mb while maintaining the same functinality.

## Currently Supported OS's

- linux-64
