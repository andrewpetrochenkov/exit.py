<!--
https://pypi.org/project/readme-generator/
https://pypi.org/project/python-readme-generator/
-->

[![](https://img.shields.io/pypi/pyversions/exit.svg?longCache=True)](https://pypi.org/project/exit/)
[![](https://img.shields.io/pypi/v/exit.svg?maxAge=3600)](https://pypi.org/project/exit/)
[![Travis](https://api.travis-ci.org/looking-for-a-job/exit.py.svg?branch=master)](https://travis-ci.org/looking-for-a-job/exit.py/)

#### Installation
```bash
$ [sudo] pip install exit
```

#### Features
+   better than `atexit.register`
+   `SIGKILL`, `SIGSTOP` or `os._exit()` not supported

#### Functions
function|`__doc__`
-|-
`exit.register(func=None, signals=[<Signals.SIGTERM: 15>])` |Register a function which will be executed on exit

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
    <a href="https://pypi.org/project/python-readme-generator/">python-readme-generator</a>
</p>