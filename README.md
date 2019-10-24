### openpyxl
---
https://github.com/chronossc/openpyxl

https://openpyxl.readthedocs.io/en/stable/

```py
// test_password_hash.py
from nose.tools import eq_

from openpyxl.shared.password_hasher import hash_password
from openpyxl.worksheet import SheetProtection

def test_hasher():
  eq_('CBEB', hash_password('test'))

def test_sheet_protection():
  protection = SheetProtection()
  protetion.password = 'test'
  eq_('CBEB', protection.password)
```

```
```

```
```


