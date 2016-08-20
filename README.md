# Easy_utill (Python3 scripts)
Easy utill provide memory usage, flush animation during calculation and so on.

## Requirements
* Python > 3.5.1

## Set Up
* Install virtualenv. (for protecting your Home environment.)
```bash
python3 -m pip install -U pip setuptools
python3 -m pip install virtualenv
# or
pip3 install virtualenv
```
* activate virtualenv
```bash
virtualenv -p python3 venv
source venv/bin/activate
# Removing virtual environment
# (venv) deactivate 
```

## build & install
```
python setup.py build
python setup.py install
```

## How to use
```python
from easyutill import cmdanime, memory

## For Command Line Animation.
anm = cmdanime.Animation()
anm.start()
# Your function here.
anm.end()

## For Memory Limit 
memlim = memory.Limit()
memlim.set(8)
# Memory Limit is 8Gb.

```

## Demo



