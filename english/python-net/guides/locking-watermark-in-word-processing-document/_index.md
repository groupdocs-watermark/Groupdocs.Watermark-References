---
title: Locking watermark in word processing document
linkTitle: "Locking watermark in"
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Lock a watermark in a Word document to restrict editing, optionally with a password, using GroupDocs.Watermark for Python via .NET."
type: docs
url: /python-net/guides/locking-watermark-in-word-processing-document/
is_root: false
weight: 190
---


To make a watermark harder to remove, you can lock it by setting `is_locked` and a `lock_type` on the watermark option ([`WordProcessingWatermarkSectionOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarksectionoptions/) or [`WordProcessingWatermarkPagesOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/)). An optional `password` is also supported.

## Add a locked watermark

  
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.options.word_processing import (
    WordProcessingLoadOptions, WordProcessingWatermarkSectionOptions, WordProcessingLockType,
)

def add_locked_watermark():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
        watermark.foreground_color = Color.red

        options = WordProcessingWatermarkSectionOptions()
        options.is_locked = True
        options.lock_type = WordProcessingLockType.ALLOW_ONLY_FORM_FIELDS
        # options.password = "p@ssw0rd"   # optional
        watermarker.add(watermark, options)

        watermarker.save("./output.docx")

if __name__ == "__main__":
    add_locked_watermark()
```

  

`document.docx` is the sample file used in this example. Click [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/adding-watermarks/add-watermarks-to-word-processing-documents/document.docx) to download it.

  
```text
Binary file (DOCX, 125 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/adding-watermarks/add-watermarks-to-word-processing-documents/locking-watermark-in-word-processing-document/add_locked_watermark/output.docx)

Available [`WordProcessingLockType`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessinglocktype/) values: `ALLOW_ONLY_FORM_FIELDS`, `ALLOW_ONLY_COMMENTS`, `ALLOW_ONLY_REVISIONS`, `READ_ONLY`, `READ_ONLY_WITH_EDITABLE_CONTENT`, and `NO_LOCK`.
