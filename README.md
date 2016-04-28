python-opensource
=================

`python-opensource` is an API Wrapper that allows you to query the
Open Source License API with Python.

Example
-------

```python
from opensource import licenses

for license in licenses.tagged("copyleft"):
    print(license.name)
```

Installing
----------

```
pip install opensource
```
