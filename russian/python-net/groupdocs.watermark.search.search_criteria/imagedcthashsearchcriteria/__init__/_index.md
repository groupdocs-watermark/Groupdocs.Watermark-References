---
title: "__init__ конструктор"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Инициализирует новый экземпляр ImageDctHashSearchCriteria с указанным путем к файлу."
type: docs
url: /ru/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Инициализирует новый экземпляр ImageDctHashSearchCriteria с указанным путем к файлу.

```python
def __init__(self, file_path):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | `str` | Путь к файлу, из которого загружается изображение. |

### Пример

```python
    from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

    criteria = ImageDctHashSearchCriteria("./logo.png")
    ```

## __init__ {#stream}

Инициализирует новый экземпляр ImageDctHashSearchCriteria с предоставленным потоком изображения.

```python
def __init__(self, stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | `io.RawIOBase` | Поток, из которого загружается изображение. |

### См. также
* class [`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)
