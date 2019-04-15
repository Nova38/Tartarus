# Tartarus
A tool to obfuscate files for CTF's or other fun things

## Install:
```shell
pip3 install tartarus
```

## How to use

``` shell
Usage: tartarus [OPTIONS] FILE

  Takes an file and randomly encodes it for obfuscation

Options:  -o, --output TEXT  output file name  -t INTEGER         How many interations
  --gzip             Adds Gunzip to operations to be used on file
  --bzip2            Adds Bzip2 to operations to be used on file
  --lzma             Adds lzma to operations to be used on file
  --zip              Adds Zip to operations to be used on file
  --xxd              Adds xxd (hexdump) to operations to be used on file  
  --base64           Adds base64 encoding to operations to be used on file
  --base32           Adds base64 encoding to operations to be used on file
  --all              Use all encretion and encoding methods above
  --help             Show this message and exit.
  ```