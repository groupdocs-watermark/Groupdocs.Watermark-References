---
title: unprotect method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/unprotect/
is_root: false
weight: 1090
---


## unprotect

Removes protection from the document regardless of the password.

```python
def unprotect(self):
    ...
```

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.wordprocessing as gwc_wp

load_options = gw.WordProcessingLoadOptions()
with gw.Watermarker("document.docx", load_options) as watermarker:
    content = watermarker.get_content(gwc_wp.WordProcessingContent)
    content.unprotect()
    watermarker.save("document.docx")
```

### See Also
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
