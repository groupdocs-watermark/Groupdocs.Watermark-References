---
title: "from_extension yöntemi"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Dosya uzantısını dosya türüne eşler."
type: docs
url: /tr/python-net/groupdocs.watermark.common/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

Dosya uzantısını dosya türüne eşler.

```python
def from_extension(cls, extension):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| extension | `str` | Dosya uzantısı (nokta "." dahil). |

**Returns:** FileType: When the file type is supported returns it, otherwise returns the default `FileType.unknown` file type.

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `extension` null veya boş bir dize olduğunda fırlatılır. |

### Ayrıca Bakınız
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
