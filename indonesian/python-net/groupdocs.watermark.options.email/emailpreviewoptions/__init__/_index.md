---
title: "__init__ konstruktor"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menginisialisasi sebuah instance baru dari kelas EmailPreviewOptions yang menyebabkan aliran output ditutup."
type: docs
url: /id/python-net/groupdocs.watermark.options.email/emailpreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Menginisialisasi instance baru dari kelas [`EmailPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailpreviewoptions/) yang menyebabkan aliran keluaran ditutup.

```python
def __init__(self, create_page_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Membuat aliran untuk pratinjau halaman tertentu. |

## __init__ {#create_page_stream-release_page_stream}

Menginisialisasi instance baru dari kelas EmailPreviewOptions yang menyebabkan aliran keluaran dikembalikan ke klien untuk penggunaan lebih lanjut.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Membuat aliran untuk pratinjau halaman tertentu. |
| release_page_stream | `ReleasePageStream` | Memberitahukan bahwa pembuatan pratinjau halaman selesai dan mendapatkan aliran output. |

### Lihat Juga
* class [`EmailPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailpreviewoptions/)
