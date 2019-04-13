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
Usage: tartarus [OPTIONS] File

Options:
  -o TEXT     output file name
  -t INTEGER  How many interations
  --gzip
  --bzip2
  --lzma
  --zip
  --all       Use all encretion and encoding methods above
  --help      Show this message and exit.
  ```