# Tartarus
A tool to obfuscate files for CTF's or other fun things

## Install:
clone the repository.
Navigate to src/python.
Then run

```shell
pip install .
```

## How to use

``` shell
Usage: tartarus [OPTIONS] INFILE

Options:
  -o, --outFile TEXT  output file name
  -t INTEGER          How many interations
  --gzip
  --bzip2
  --lzma
  --zip
  --xxd
  --all               Use all encretion and encoding methods above
  --help              Show this message and exit.
  ```