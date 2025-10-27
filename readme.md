# Messiah

A simple base64 decoder / encoder written in C

```bash
make
make test
./messiah --help
```

```bash
Usage: messiah [MODE] [ENCODING]
This program reads from stdin and writes to stdout

 Modes:
  -e, --encode     encoding mode
  -d, --decode     decoding mode
  -h, --help       get some help

 Encodings:
  -b64            base64 encoding

 Examples:
  echo -n "Example string for encoding" | messiah -e -b64
  echo -n "VGhlIG1lc3NpYWggY29udmVydHM=" | messiah -d -b64  
```
