# zim-testing-suite

This repository contains testing zim files for libzim and other openzim repositories.


## How to use it.

[libzim](https://github.com/openzim/libzim) test suite need some test zim files to work.

This repository provides them.

Get the zim files in the `data` directory and copy them in a directory.
Create a environment variable named `ZIM_TEST_DATA_DIR` pointing to this directory.


## Developer warning.

Scripts in the `scripts` directory are the ones used to generate the zim in `data`.
However, test zim files **must not** be changed (and so must not be regenerated).
Be careful with the scripts and do not regenerated the test zims unless you know what
you are doing.
