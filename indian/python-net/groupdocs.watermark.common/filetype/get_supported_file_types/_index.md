---
title: "get_supported_file_types मेथड"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "समर्थित फ़ाइल प्रकारों को प्राप्त करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.common/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

समर्थित फ़ाइल प्रकारों को प्राप्त करता है।

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable[FileType]: The sequence of the supported file types.

### उदाहरण

```python
    from groupdocs.watermark.common import FileType

    def list_supported_formats():
        # लाइब्रेरी द्वारा खोले जा सकने वाले प्रत्येक फ़ाइल प्रकार को सूचीबद्ध करें
        supported_file_types = FileType.get_supported_file_types()
        for file_type in sorted(supported_file_types, key=lambda x: x.extension):
            print(file_type)

    if __name__ == "__main__":
        list_supported_formats()
    ```

### संबंधित देखें
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
