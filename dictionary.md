# Dictionary

## Important feature

1. _Fixed order dictionary after Python3.6+_ 

{% hint style="info" %}
Alternative at other version

```python
from collections import OrderedDict

dic =  OrderedDict()
d["dict_keyname"] = dic_value
```
{% endhint %}

## Useful functions

1. The method **get\(\)** returns a value for the given key. If key is not available then returns default value None.

```python
dict.get(key, default=None)
```

2. The method **setdefault\(\)** is similar to get\(\), but will set dict\[key\] = default if key is not already in dict.

```python
dict.setdefault(key, default = None)
```

3. The method **update\(\)** adds dictionary dict2's key-values pairs in to dict. This function does not return anything.

```python
dict.update(dict2)
```

