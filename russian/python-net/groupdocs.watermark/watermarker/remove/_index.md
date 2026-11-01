---
title: "метод remove"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Удаляет водяной знак из документа."
type: docs
url: /ru/python-net/groupdocs.watermark/watermarker/remove/
is_root: false
weight: 1100
---


## remove {#possible_watermark}

Удаляет водяной знак из документа.

Узнайте больше об удалении водяных знаков: Удаление найденных водяных знаков.

```python
def remove(self, possible_watermark):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| possible_watermark | `PossibleWatermark` | Водяной знак для удаления. |

### Пример

```python
from groupdocs.watermark import Watermarker

def remove_first_watermark():
    with Watermarker("./document.pdf") as watermarker:
        watermarks = watermarker.search()
        if watermarks:
            watermarker.remove(watermarks[0])
        watermarker.save("./output.pdf")
```

## remove {#possible_watermarks}

Удаляет из документа все водяные знаки из коллекции.

Узнайте больше об удалении водяных знаков в документации GroupDocs.

```python
def remove(self, possible_watermarks):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| possible_watermarks | `PossibleWatermarkCollection` | Коллекция водяных знаков для удаления. |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def remove_watermark():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search()
        # Удаляйте в обратном порядке, чтобы индексы оставались корректными.
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")
```

### См. также
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
