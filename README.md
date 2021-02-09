# Python 3 Conan Package

[![Build Status](https://travis-ci.org/dcvetko/conan-python3.svg?branch=master)](https://travis-ci.org/dcvetko/conan-python3)

Provides a conan package for Python 3 (https://github.com/python/cpython).

## How-to

Export the package to a user/channel combination:
```
conan export <user>/<channel>
```

Build the package:
```
conan install python3/3.6.1@<user>/<channel> --build -g virtualenv
```

Activate the package:
```
source ./activate.sh
```

Verify that python3.6 points to the correct path:
```
which python3.6
echo $PYTHONPATH
```
