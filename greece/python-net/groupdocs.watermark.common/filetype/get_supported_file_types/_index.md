---
title: "get_supported_file_types μέθοδος"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Ανακτά τους υποστηριζόμενους τύπους αρχείων."
type: docs
url: /el/python-net/groupdocs.watermark.common/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

Ανακτά τους υποστηριζόμενους τύπους αρχείων.

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable[FileType]: The sequence of the supported file types.

### Παράδειγμα

```python
    from groupdocs.watermark.common import FileType

    def list_supported_formats():
        # Απαριθμίστε κάθε τύπο αρχείου που μπορεί να ανοίξει η βιβλιοθήκη
        supported_file_types = FileType.get_supported_file_types()
        for file_type in sorted(supported_file_types, key=lambda x: x.extension):
            print(file_type)

    if __name__ == "__main__":
        list_supported_formats()
    ```

### Δείτε επίσης
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
