---
title: "from_extension метод"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Сопоставляет расширение файла типу файла."
type: docs
url: /ru/python-net/groupdocs.watermark.common/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

Сопоставляет расширение файла типу файла.

```python
def from_extension(cls, extension):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| extension | `str` | Расширение файла (включая точку "."). |

**Returns:** FileType: When the file type is supported returns it, otherwise returns the default `FileType.unknown` file type.

| Вызывает | Описание |
| :- | :- |
| `ValueError` | Выбрасывается, когда `extension` имеет значение null или пустую строку. |

### См. также
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
