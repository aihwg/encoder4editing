# About This Repository

This repository is a fork of the original repository [https://github.com/omertov/encoder4editing.git] and has been independently edited. 

## Changes
utils/alignment/77:
- original
  img = img.resize(rsize, PIL.Image.ANTIALIAS)
- edited
  img = img.resize(rsize, PIL.Image.LANCZOS)