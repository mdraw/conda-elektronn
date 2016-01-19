# conda-elektronn
[Conda](https://github.com/conda/conda) recipes for [ELEKTRONN](https://github.com/ELEKTRONN/ELEKTRONN).

Conda packages for ELEKTRONN are now online at [anaconda.org](http://anaconda.org/elektronn/elektronn). You can install them by running

    $ conda config --add channels elektronn
    $ conda install elektronn

Currently the only officially supported platform is linux-x86_64. Support for Windows x64 *may* be added some day if there is demand.

## Building and installing the packages manually:

Stable releases:

    $ git clone https://github.com/mdraw/conda-elektronn.git
    $ cd conda-elektronn
    $ conda build elektronn
    $ conda install --use-local elektronn

Git version:

    $ git clone https://github.com/mdraw/conda-elektronn.git
    $ cd conda-elektronn
    $ conda build elektronn-git
    $ conda install --use-local elektronn-git
