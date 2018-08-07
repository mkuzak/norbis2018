# Modules

[Python Modules](https://github.com/mkuzak/python-modules/blob/master/python-modules.md)

# Packages

[Python Packaging Tutorial](https://python-packaging-tutorial.readthedocs.io/en/latest/setup_py.html)

* download Capitalize example
from [here](https://python-packaging-tutorial.readthedocs.io/en/latest/_downloads/capitalize.zip)

Include data file in the package.

```py
setup(...,
      packages=['mypkg'],
      package_dir={'mypkg': 'src/mypkg'},
      package_data={'mypkg': ['data/*.dat']},
      )
```
