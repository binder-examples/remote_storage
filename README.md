# Example Binder using remote storage

[![Binder](http://mybinder.org/badge.svg)](http://beta.mybinder.org/v2/gh/binder-examples/remote_storage/master)

A Binder-compatible repo that shows accessing data from remote sources.

Access this Binder at the following URL:

http://beta.mybinder.org/v2/gh/binder-examples/remote_storage/master


## Notes
The notebooks use `boto` and `requests` to load both images and tables from S3.
The image loading makes use of `PIL` and the table loading
makes use of `pandas`.
