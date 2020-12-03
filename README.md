<!--
https://readme42.com
-->


[![](https://img.shields.io/pypi/v/exit.svg?maxAge=3600)](https://pypi.org/project/exit/)
[![](https://img.shields.io/badge/License-Unlicense-blue.svg?longCache=True)](https://unlicense.org/)
[![](https://github.com/andrewp-as-is/exit.py/workflows/tests42/badge.svg)](https://github.com/andrewp-as-is/exit.py/actions)

### Installation
```bash
$ [sudo] pip install exit
```

#### Features
+   better than `atexit.register`
+   `SIGKILL`, `SIGSTOP` or `os._exit()` not supported

#### Examples
```python
>>> import exit
>>> def on_exit():
    print("goodbye world")

>>> exit.register(on_exit)
```

#### Links
+   [How to always execute exit functions in Python](http://grodola.blogspot.com/2016/02/how-to-always-execute-exit-functions-in-py.html)

<p align="center">
    <a href="https://readme42.com/">readme42.com</a>
</p>
