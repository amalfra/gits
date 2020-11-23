gits
========
[![GitHub release](https://img.shields.io/github/release/amalfra/gits.svg)](https://github.com/amalfra/gits/releases)

*gits* is a simple bash script to sync specified git repo(s). It will pull and rebase code from your remote named `main` and push it to `origin`.

## Installation
Clone the repo or download the file named `gits` from this repo!

## Usage
Just configure the env variable `GITS_GIT_FOLDERS` with the absolute paths to your git repo folders. For eg in `.bashrc` add below line
```sh
export GITS_GIT_FOLDERS="/home/amal/myProject"
```
Mutiple folders can be given by comma seperated values
```sh
export GITS_GIT_FOLDERS="/home/amal/myProject1, /home/amal/myProject2"
```
*gits* will check for a git repo in all provided folders and if it does not exist, then will do sync in all it's sub folders. 

You can also sync specific folder by using commandline parameter. For eg
```sh
gits /home/amal/myProject
```
will do sync just on ```/home/amal/myProject``` folder.

## Development
Questions, problems or suggestions? Please post them on the [issue tracker](https://github.com/amalfra/gits/issues).

You can contribute changes by forking the project and submitting a pull request. Feel free to contribute :heart_eyes:

UNDER MIT LICENSE
=================

The MIT License (MIT)

Copyright (c) 2016 Amal Francis

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

