---
layout: post
title: "Zopfli and Zopflipng Windows Binaries"
categories: [Windows_Binaries, Google]
tags: [Google, Compression]
---

# Zopfli

Zopfli Compression Algorithm is a compression library programmed in C to perform
very good, but slow, deflate or zlib compression.

Zopfli Github Repositiory: [https://github.com/google/zopfli](https://github.com/google/zopfli)



## Download
Compiled at 2021/10/31

Cross Compiled using WSL (UBUNTU)

[Zopfli Download](https://drpleaserespect.github.io/drpleaserespect-webassets/compiled_binaries/google/zopfli.exe)

[Virustotal Results](https://www.virustotal.com/gui/file/aaba8a9078d8565d29a944c62b24a3790db8d84444cc06e6903d06361a1db62b/detection)

# ZopfliPNG
ZopfliPNG is a command line program to optimize the Portable Network Graphics
(PNG) images. This version has the following features:
- uses Zopfli compression for the Deflate compression,
- compares several strategies for choosing scanline filter codes,
- chooses a suitable color type to losslessly encode the image,
- removes all chunks that are unimportant for the typical web use (metadata,
  text, etc...),
- optionally alters the hidden colors of fully transparent pixels for more
  compression, and,
- optionally converts 16-bit color channels to 8-bit.

ZopfliPNG Github Repository: [https://github.com/google/zopfli/blob/master/README.zopflipng](https://github.com/google/zopfli/blob/master/README.zopflipng)

## Download
Compiled at 2021/10/31

Cross Compiled using WSL (UBUNTU)

[ZopfliPNG Download](https://drpleaserespect.github.io/drpleaserespect-webassets/compiled_binaries/google/zopflipng.exe)

[Virustotal Results](https://www.virustotal.com/gui/file/99794275d0cd99f5eaf6e91ce7425407341aadf917f658d55c0f36e913696460/detection)