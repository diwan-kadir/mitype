# mitype : Typing Speed Test right in your terminal

[![Generic badge](https://img.shields.io/badge/AUTHOR-MITHIL-BLUE.svg)](https://shields.io/)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![PyPI Latest Release](https://img.shields.io/pypi/v/mitype.svg)](https://pypi.org/project/mitype/)
[![Package Status](https://img.shields.io/pypi/status/mitype.svg)](https://pypi.org/project/mitype/)
[![License](https://img.shields.io/pypi/l/mitype.svg)](https://github.com/mithil467/mitype/blob/master/LICENSE.txt)
[![GitHub release](https://img.shields.io/github/release/mithil467/mitype.svg)](https://GitHub.com/mithil467/mitype/releases/)
[![GitHub stars](https://img.shields.io/github/stars/mithil467/mitype.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/mithil467/mitype/stargazers/)

## What is it?

**mitype** is a Python package to test (and improve) your typing speed in your terminal. Test text is taken from data/db database which is a collection of 6000 strings taken from typeracerdata.com (I do not own any of the strings and the text content is not given with my license).

## Where to get it

The source code is hosted on GitHub at:
https://github.com/mithil467/mitype

Binary installers for the latest released version are available at the [Python
package index](https://pypi.org/project/mitype/#files).

```shy
pip install mitype
```

That's all if you are on linux.  
If you are on windows, you also need windows-curses, which can be installed from pypi:

```shy
pip install windows-curses
```

## How to run it?

Once installed, you can run it by

```shy
python -m mitype
```
You can quit the app anytime by pressing ESC key.

## Dependencies

For windows only
- [windows-curses](https://pypi.org/project/windows-curses/)

## Installation from sources

To install mitype from source - 

In the `mitype` directory (same one where you found this file after
cloning the git repo), execute:

```sh
python setup.py install
```


## License
[GPL](LICENSE.txt)
