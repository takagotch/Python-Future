### python-fucture
---
http://python-future.org/index.html

```py
from __future__ import absolute_import
from __future__ import division
from __future__ import print_function
from __future__ import unicode_literals

from builtins import open
from builtins import str

from future import standard_library
standard_library.install_aliases()

import ConfigParser

class Upper(object):
  def __init__(self,iterable):
    self.iter = iter(iterable)
  def next(self):
    return next(self._iter).upper()
  def __iter__(self):
    return self
itr = Upper('hello')
print letter in itr:
  print letter,
```

```
```

```
```


