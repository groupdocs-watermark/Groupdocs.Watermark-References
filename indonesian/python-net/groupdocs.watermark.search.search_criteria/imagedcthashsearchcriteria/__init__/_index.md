---
title: "__init__ konstruktor"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menginisialisasi instance ImageDctHashSearchCriteria baru dengan jalur file yang ditentukan."
type: docs
url: /id/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Menginisialisasi instance ImageDctHashSearchCriteria baru dengan jalur file yang ditentukan.

```python
def __init__(self, file_path):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | `str` | Path file untuk memuat gambar. |

### Contoh

```python
    from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

    criteria = ImageDctHashSearchCriteria("./logo.png")
    ```

## __init__ {#stream}

Menginisialisasi instance ImageDctHashSearchCriteria baru dengan aliran gambar yang disediakan.

```python
def __init__(self, stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | `io.RawIOBase` | Stream untuk memuat gambar. |

### Lihat Juga
* class [`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)
