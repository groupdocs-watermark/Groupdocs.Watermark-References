---
title: "طريقة remove"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يزيل علامة مائية من المستند."
type: docs
url: /ar/python-net/groupdocs.watermark/watermarker/remove/
is_root: false
weight: 1100
---


## remove {#possible_watermark}

يزيل علامة مائية من المستند.

تعرف على المزيد حول إزالة العلامات المائية: إزالة العلامات المائية المكتشفة.

```python
def remove(self, possible_watermark):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| possible_watermark | `PossibleWatermark` | العلامة المائية التي يجب إزالتها. |

### مثال

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

يزيل جميع العلامات المائية في المجموعة من المستند.

تعرف على المزيد حول إزالة العلامات المائية في وثائق GroupDocs.

```python
def remove(self, possible_watermarks):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| possible_watermarks | `PossibleWatermarkCollection` | مجموعة العلامات المائية التي يجب إزالتها. |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def remove_watermark():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search()
        # قم بالإزالة بترتيب عكسي للحفاظ على صحة الفهارس
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")
```

### انظر أيضًا
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
