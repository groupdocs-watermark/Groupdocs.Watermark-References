---
title: "Kelas IDocumentInfo"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menyediakan metode yang diperlukan untuk mengambil informasi dasar dokumen."
type: docs
url: /id/python-net/groupdocs.watermark.common/idocumentinfo/
is_root: false
weight: 70
---


## IDocumentInfo class

Menyediakan metode yang diperlukan untuk mengambil informasi dasar dokumen.

Pelajari lebih lanjut: Dapatkan info dokumen.

Tipe IDocumentInfo menampilkan anggota-anggota berikut:

### Properti
| Properti | Deskripsi |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/file_type/) | Deskripsi format file. |
| [is_encrypted](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/is_encrypted/) | Properti menunjukkan apakah dokumen terenkripsi dan memerlukan kata sandi untuk dibuka. |
| [page_count](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/page_count/) | Jumlah total halaman. |
| [pages](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/pages/) | Koleksi deskripsi halaman dokumen. |
| [size](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/size/) | Ukuran dokumen dalam byte. |

### Contoh

```python
from groupdocs.watermark import Watermarker

with Watermarker(r"D:\input.pdf") as watermarker:
    doc_info = watermarker.get_document_info()
    print(f"Document size: {doc_info.size}")
    print(f"Document format: {doc_info.file_type.file_format_name}")
    print(f"Document contains {doc_info.page_count} pages")
```

### Lihat Juga
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
