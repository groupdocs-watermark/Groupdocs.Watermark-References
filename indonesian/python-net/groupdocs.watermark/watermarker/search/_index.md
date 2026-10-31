---
title: "metode search"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mencari semua watermark yang mungkin dalam dokumen."
type: docs
url: /id/python-net/groupdocs.watermark/watermarker/search/
is_root: false
weight: 1190
---


## search

Mencari semua watermark yang mungkin dalam dokumen.

Pencarian dilakukan pada objek yang ditentukan dalam [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Pelajari lebih lanjut tentang mencari watermark https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self):
    ...
```

**Returns:** The collection of possible watermarks.

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def search_by_text():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_text()
```

## search {#search_criteria}

Mencari watermark yang mungkin sesuai dengan kriteria pencarian yang ditentukan.

Pencarian dilakukan pada objek yang ditentukan dalam [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Pelajari lebih lanjut tentang mencari watermark: https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self, search_criteria):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | Kriteria pencarian yang akan digunakan. |

**Returns:** The collection of possible watermarks.

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def search_by_text():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_text()
```

### Lihat Juga
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
