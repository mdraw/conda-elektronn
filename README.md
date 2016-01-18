# conda-elektronn
[conda](https://github.com/conda/conda) recipes for [ELEKTRONN](https://github.com/ELEKTRONN/ELEKTRONN).

## Building and installing (requires anaconda2 or miniconda2):

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
