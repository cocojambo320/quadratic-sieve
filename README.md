# quadratic-sieve

An implementation of quadratic sieve algorithm for factorization written in Python.

## Table of contents
* [Technologies](#technologies)
* [Testing](#testing)
* [Install](#install)
* [Run](#run)
* [Options](#options)


## Technologies
Technologies used:
* Python version: 3.9.1
* numpy version: 1.20.1
  
Development:
* py.test verion: 6.2.2
* wheel version: 0.36.2


## Install
```
$ pip install quadratic_sieve
```

## Run
```
$ quadratic_sieve 12666334082118686111
```

## Running options
```
$ usage: quadratic_sieve [-h] [-b SMOOTHNESS] [-s BASE_SIZE] [-l] n
$ 
$ positional arguments:
$   n                     Number to factorize.
$
$ optional arguments:
$   -h, --help            show this help message and exit
$   -b SMOOTHNESS, --smoothness SMOOTHNESS
$                         Set smoothness bound.
$   -s BASE_SIZE, --base_size BASE_SIZE
$                         Set the size of generated QS base.
$   -l, --loud            Display messages while computing.
```

## Development
### Testing
Running the tests:
```
$ pip install pytest
$ pytest
```

### Distribution building
```
$ pip install wheel
$ python setup.py dist_wheel
```

### Installing the built distribution
```
$ pip install dist/quadratic_sieve-0.1.1-py3-none-any.whl
```