---
title: "metode search"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menemukan watermark yang mungkin sesuai dengan kriteria pencarian yang ditentukan."
type: docs
url: /id/python-net/groupdocs.watermark.contents/contentpart/search/
is_root: false
weight: 1030
---


## search {#search_criteria}

Menemukan watermark yang mungkin sesuai dengan kriteria pencarian yang ditentukan. Pencarian dilakukan pada objek-objek yang terdaftar dalam [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/).

```python
def search(self, search_criteria):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | Kriteria pencarian yang akan digunakan. |

**Returns:** The collection of the possible watermarks.

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
    print("Found", len(possible), "possible watermark(s)")
```

## search

Menemukan semua watermark yang mungkin dalam konten.

Pencarian dilakukan pada objek yang ditentukan dalam [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

```python
def search(self):
    ...
```

**Returns:** Iterable[Watermark]: The collection of the possible watermarks.

### Lihat Juga
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
