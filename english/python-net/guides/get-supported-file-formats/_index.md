---
title: Get supported file formats
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/guides/get-supported-file-formats/
is_root: false
weight: 410
---


Get the list of all supported file formats.

Quickly retrieve the complete list of file formats supported by GroupDocs.Watermark. This allows Python developers to dynamically check compatibility before processing documents.

```python
from groupdocs.watermark.common import FileType

supported = FileType.get_supported_file_types()
for ft in supported:
    print(ft)
```

🔹 Use case: Build flexible applications that can automatically validate user-uploaded files and inform them if watermarking is supported.
