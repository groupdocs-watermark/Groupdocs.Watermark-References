---
title: "remove metodu"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Belgeden bir filigranı kaldırır."
type: docs
url: /tr/python-net/groupdocs.watermark/watermarker/remove/
is_root: false
weight: 1100
---


## remove {#possible_watermark}

Belgeden bir filigranı kaldırır.

Filigranları kaldırma hakkında daha fazla bilgi edinin: Bulunan filigranların kaldırılması.

```python
def remove(self, possible_watermark):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| possible_watermark | `PossibleWatermark` | Kaldırılacak filigran. |

### Örnek

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

Belgeden koleksiyondaki tüm filigranları kaldırır.

GroupDocs belgelerinde filigranları kaldırma hakkında daha fazla bilgi edinin.

```python
def remove(self, possible_watermarks):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| possible_watermarks | `PossibleWatermarkCollection` | Kaldırılacak filigranların koleksiyonu. |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def remove_watermark():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search()
        # Dizinlerin geçerli kalması için ters sırada kaldırın
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")
```

### Ayrıca Bakınız
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
