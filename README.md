# HElmholtz Rich MEtadata Software publication (HERMES)

This code repository contains the [Sphinx](https://www.sphinx-doc.org), [MyST](https://myst-parser.readthedocs.io) and [sphinx-book-theme](https://sphinx-book-theme.readthedocs.io) based website for the HERMES project.

**Please visit https://project.software-metadata.pub for further reading.**

## Build locally

To use the convenient `Makefile`, you need to have `make` installed.
[You might want to use a virtual Python environment.](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/)

```shell

pip install -r requirements.txt
make html

- OR - 

pip install -r requirements.txt
make livehtml

```