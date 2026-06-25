---
title: protect method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect/
is_root: false
weight: 1050
---


## protect {#protection_type-password}

Protects the document from changes and sets a protection password.

To have the content of the document editable use appropriate method of adding watermark with `WordProcessingLockType.allow_only_form_fields` or `WordProcessingLockType.read_only_with_editable_content` parameter.

```python
def protect(self, protection_type, password):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| protection_type | `WordProcessingProtectionType` | Specifies the protection type for the document. |
| password | `str` | The password to protect the document with. |

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.wordprocessing as gwc_wp

load_options = gw.WordProcessingLoadOptions()
with gw.Watermarker("document.docx", load_options) as watermarker:
    content = watermarker.get_content(gwc_wp.WordProcessingContent)
    content.protect(gwc_wp.WordProcessingProtectionType.READ_ONLY, "7654321")
    watermarker.save("document.docx")
```

### See Also
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
