# ipython-autotime

Time everything in IPython. Original https://github.com/cpcloud/ipython-autotime

Updated to add a line break and removed the start time.

## Installation:

```console
$ python -m pip install git+https://github.com/chaseedge/ipython-autotime.git
```

## Examples

```python
In [1]: %load_ext autotime

time: 264 µs

In [2]: x = 1

time: 416 µs

In [3]: x / 0
---------------------------------------------------------------------------
ZeroDivisionError                         Traceback (most recent call last)
<ipython-input-3-034eb0c6102b> in <module>
----> 1 x/0

ZeroDivisionError: division by zero

time: 88.7 ms
```

## Want to turn it off?

```python
In [4]: %unload_ext autotime
```
