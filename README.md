# ISO Country Codes
[![Build Status](https://travis-ci.org/geoffreybauduin/python-isocountrycode.svg?branch=master)](https://travis-ci.org/geoffreybauduin/python-isocountrycode)

Tools to deal with ISO country codes in Python

`pip install isocountrycode`

## How to use it ?

```python
from isocountrycode import Alpha2

print("I'm located in {}".format(Alpha2.United_States_Of_America.value))
```

# Contributing

Feel free to open a PR or an issue if you feel like discussing about something.

To launch unit tests (very simple):

`tox`

# License

MIT License

Copyright (c) 2017 Geoffrey Bauduin

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
