# Example Binder using remote storage

A Binder-compatible repo that shows accessing data from remote sources.

[![Binder](http://mybinder.org/badge.svg)](http://beta.mybinder.org/v2/gh/binder-examples/remote-storage/master)

Access this Binder at the following URL:

http://beta.mybinder.org/v2/gh/binder-examples/requirements/master


# Notes
The notebooks use `boto` and `requests` to load both images and tables from S3
and Google Storage. The image loading makes use of `PIL` and the table loading
makes use of `pandas`. In both cases the data have been made publicly available.
