# pytables-testpypi
Download and pip install packages from testpypi (to test pytables releases)

Travis CI https://travis-ci.org/tomkooij/pytables-testpypi

How-to::

$ python setup.py sdist

Upload the package to testPyPI::

$ twine upload --repository-url https://test.pypi.org/legacy/ tables-X.Y.Z.tar.gz

Modify .travis.yml (and appveyor.yml if I ever get around creating it) and monitor the CI
