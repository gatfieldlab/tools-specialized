# gatlab-tools-specialized

This package provides a collection of specialized data structures and utility functions for memory intensive objects

## Installation

Using `pip`:

    pip install -e 'git+https://github.com/gatfieldlab/tools_specialized#egg=gatlab-tools-specialized'

or using our Python Package Server as an extra index:

    pip install gatlab-tools-specialized --extra-index-url https://gatfieldlab.github.io/python-package-server/
    
From `setup.py` with `setuptools`:

    install_requires = ['gatlab-tools-specialized-VERSION']
    dependency_links = ['https://github.com/gatfieldlab/tools_specialized/tarball/master#egg=gatlab-tools-specialized-VERSION']

Replace `VERSION` with the current version, for example 0.1.0.

To use a specific version from previous releases:

    dependency_links = ['https://github.com/gatfieldlab/tools_specialized/archive/v0.1.0.tar.gz#egg=gatlab-tools-specialized-0.1.0']
    

Support for `dependency_links` and `setuptools` will not be continued and will be removed in the next releases.

## Usage

Modules should be imported using the `gatlab_tools` namespace:

    from gatlab_tools.specialized import cached_objects

