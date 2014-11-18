sample_sphinxcontrib.spelling
=============================

Sample code for sphinxcontrib.spelling.

## About sphinxcontrib.spelling

* http://sphinxcontrib-spelling.readthedocs.org/en/latest/

## Installation

```sh
$ mkvirtualenv sample
(sample)$ pip install -r requirements.txt
```

## Build html and check spelling

```sh
(sample)$ cd doc
(sample)$ make html
```

## Result file

```sh
(sample)$ cat _build/spelling/output.txt
index.rst:20: (Shpinx)
```
