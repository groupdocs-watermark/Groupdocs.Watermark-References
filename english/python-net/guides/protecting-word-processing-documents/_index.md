---
title: Protecting word processing documents
linkTitle: "Protecting word"
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Protect and unprotect Word documents with a protection type and password using GroupDocs.Watermark for Python via .NET."
type: docs
url: /python-net/guides/protecting-word-processing-documents/
is_root: false
weight: 230
---


Beyond locking an individual watermark, you can protect the whole document. `Watermarker.get_content()` returns a [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/) with `protect()` and `unprotect()` methods.

## Protect a document

The example sets read-only protection with a password.

  
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions
from groupdocs.watermark.contents.word_processing import WordProcessingProtectionType

def protect_document():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        content = watermarker.get_content()
        content.protect(WordProcessingProtectionType.READ_ONLY, "p@ssw0rd")
        watermarker.save("./output.docx")

if __name__ == "__main__":
    protect_document()
```

  

`document.docx` is the sample file used in this example. Click [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/adding-watermarks/add-watermarks-to-word-processing-documents/document.docx) to download it.

  
```text
Binary file (DOCX, 119 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/adding-watermarks/add-watermarks-to-word-processing-documents/protecting-word-processing-documents/protect_document/output.docx)

Available [`WordProcessingProtectionType`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingprotectiontype/) values: `READ_ONLY`, `ALLOW_ONLY_FORM_FIELDS`, `ALLOW_ONLY_COMMENTS`, and `ALLOW_ONLY_REVISIONS`.

## Unprotect a document

  
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

def unprotect_document():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        content = watermarker.get_content()
        content.unprotect()
        watermarker.save("./output.docx")

if __name__ == "__main__":
    unprotect_document()
```

  

`document.docx` is the sample file used in this example. Click [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/adding-watermarks/add-watermarks-to-word-processing-documents/document.docx) to download it.

  
```text
Binary file (DOCX, 118 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/adding-watermarks/add-watermarks-to-word-processing-documents/protecting-word-processing-documents/unprotect_document/output.docx)
