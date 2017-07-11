# opus-convert-dir

This is a script I wrote to transcode my collection of [FLAC](https://xiph.org/flac) to [OPUS](https://opus-codec.org)

The usage is fairly simple, but here's an example:

`opus-convert-dir music-folder 160k output-folder`

to update (overwrite) your transcodes, to change the bitrate for example:

`opus-convert-dir music-folder 96k output-folder -y`
