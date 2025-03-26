---
title: from_extension method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.common/filetype/from_extension/
is_root: false
weight: 30
---

## from_extension {#str}

Maps the file extension to the file type.


### Returns 


When the file type is supported returns it, otherwise returns the default [`FileType.Unknown`](/watermark/python-net/groupdocs.watermark.common/filetype) file type.


```python
def from_extension(self, extension):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| extension | str | The file extension (including the period "."). |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `extension` is null or empty string. |





### See Also
* module [`groupdocs.watermark.common`](../../)
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype)
