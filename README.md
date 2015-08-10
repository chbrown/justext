# jusText

You probably want miso-belica's [jusText](https://github.com/miso-belica/jusText), which is far better maintained than this repository.

---

## Overview

This is a slight patching of the original repository from [googlecode](http://code.google.com/p/justext/).

The original author is [Jan Pomikalek](mailto:jan.pomikalek@gmail.com), and the site is: [code.google.com/p/justext/](http://code.google.com/p/justext/). However, I was having trouble sending his code unicode directly (it seems it assumes it always gets non-unicode), which wasn't working for my application.

So now I check whether the input is unicode.

## Requires:

- lxml (>=2.2.4)

## Installation

To install the package type:

    python setup.py install

Or

    python setup.py develop

Or

    pip install git+https://github.com/chbrown/justext.git

## Basic usage:

    justext -s English YourPage.html

For usage information see:

    justext --help

## Alternatives:

+ Python
    * [python-goose](https://github.com/grangier/python-goose)
    * [decruft](https://github.com/dcramer/decruft)
+ Java
    * [Boilerpipe](https://code.google.com/p/boilerpipe/)
        - [Python wrapper](https://github.com/misja/python-boilerpipe)
