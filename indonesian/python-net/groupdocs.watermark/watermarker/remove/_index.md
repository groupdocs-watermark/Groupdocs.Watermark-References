---
title: "metode remove"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menghapus watermark dari dokumen."
type: docs
url: /id/python-net/groupdocs.watermark/watermarker/remove/
is_root: false
weight: 1100
---


## remove {#possible_watermark}

Menghapus watermark dari dokumen.

Pelajari lebih lanjut tentang menghapus watermark: Menghapus watermark yang ditemukan.

```python
def remove(self, possible_watermark):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| possible_watermark | `PossibleWatermark` | Watermark yang akan dihapus. |

### Contoh

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

Menghapus semua watermark dalam koleksi dari dokumen.

Pelajari lebih lanjut tentang menghapus watermark di dokumentasi GroupDocs.

```python
def remove(self, possible_watermarks):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| possible_watermarks | `PossibleWatermarkCollection` | Koleksi watermark yang akan dihapus. |

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def remove_watermark():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search()
        # Hapus dalam urutan terbalik untuk menjaga indeks tetap valid
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")
```

### Lihat Juga
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
