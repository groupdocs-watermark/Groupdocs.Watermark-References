---
title: Protecting word processing documents
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/guides/protecting-word-processing-documents/
is_root: false
weight: 230
---


You can protect Word documents with a password or remove protection. Supported protection types:

- AllowOnlyRevisions
- AllowOnlyComments
- AllowOnlyFormFields
- ReadOnly

## Protecting a document
This sample enables document protection with a specified protection type and password.

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.wordprocessing as gwc_wp

load_options = gw.WordProcessingLoadOptions()
with gw.Watermarker("document.docx", load_options) as watermarker:
    content = watermarker.get_content(gwc_wp.WordProcessingContent)
    content.protect(gwc_wp.WordProcessingProtectionType.READ_ONLY, "7654321")
    watermarker.save("document.docx")
```

## Unprotecting a document
This sample removes protection from the document so it can be edited freely.

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.wordprocessing as gwc_wp

load_options = gw.WordProcessingLoadOptions()
with gw.Watermarker("document.docx", load_options) as watermarker:
    content = watermarker.get_content(gwc_wp.WordProcessingContent)
    content.unprotect()
    watermarker.save("document.docx")
```
