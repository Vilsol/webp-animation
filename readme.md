
# webp-animation

Golang binding to **libwebp**, **libpng** and **giflib** library

This package implements functions (not all) which are required to convert GIF to WEBP animation, especially the functions that were used for this example: https://github.com/webmproject/libwebp/blob/0.6.1/examples/gif2webp.c.   
Binding to libpng helps to create new webp animation from png images.


## Installation

Get package: ```go get github.com/sizeofint/webp-animation```

dependencies:

- libraries: libwebp 0.6.1, giflib 5.1, zlib 1.2.11(required for libpng), libpng 1.6.36


Package provides prebuilt dependencies for Linux, but if you want to rebuild by your own, run [deps/build-deps-linux.sh](deps/build-deps-linux.sh)  
  


## Implementations

[gif-to-webp](https://github.com/sizeofint/gif-to-webp  "Golang convert GIF to WEBP") library based on this library
