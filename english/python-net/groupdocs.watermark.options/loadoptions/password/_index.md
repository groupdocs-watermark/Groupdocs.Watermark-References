---
title: password property
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.options/loadoptions/password/
is_root: false
weight: 60
---

## password property


Gets or sets the password for opening an encrypted document.

### Remarks 


The password be null or empty string. The default value is null.
If the content is not encrypted, set this to null or empty string.

### Example 


Load a content protected with a password.
### Definition:
```python
@property
def password(self):
    ...
@password.setter
def password(self, value):
    ...
```

### See Also
* module [`groupdocs.watermark.options`](../../)
* class [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions)
