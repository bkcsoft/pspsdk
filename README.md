Docker-image for PSPSDK
=======================

Complete toolchain and sdk for PSP homebrew-development

Usage
=====

Run this in where your Makefile lives
```
docker run -it --rm -v $(pwd):/data/build bkcsoft/pspsdk make
```
