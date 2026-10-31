---
title: "طريقة from_extension"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يقوم بربط امتداد الملف بنوع الملف."
type: docs
url: /ar/python-net/groupdocs.watermark.common/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

يقوم بربط امتداد الملف بنوع الملف.

```python
def from_extension(cls, extension):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| extension | `str` | امتداد الملف (بما في ذلك النقطة "."). |

**Returns:** FileType: When the file type is supported returns it, otherwise returns the default `FileType.unknown` file type.

| يطرح | الوصف |
| :- | :- |
| `ValueError` | يُرمى عندما تكون `extension` فارغة أو null. |

### انظر أيضًا
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
