# Hex

A minimal command line tool for encoding and decoding hex codes.

This is just a tool I created for myself because I could never remember how to
encode or decode arbitrary hex data from the command line. You're welcome to
use it too.

## Usage

There are two modes, `--encode` and `--decode`.

For example, to encode binary data from `data.bin` into hex in `data.txt`, run

```
hex --encode < data.bin > data.txt
```

To decode hex from `data.txt` into binary data in `data.bin`, run

```
hex --decode < data.txt > data.bin
```

Note that all data flows through `stdin` and `stdout`, so you can easily
compose this tool with whatever other programs you like.

## Installation

You're on your own here. I built this project using `clang` and `make`, so if
you have those installed, it-will-probably-just-work. Shouldn't be too hard to
build it yourself using other tools, though.

## License

This software is provided under the [MIT License](LICENSE). Go wild.

