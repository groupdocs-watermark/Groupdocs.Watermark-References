---
title: "properti create_page_stream"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Delegate pembuatan aliran halaman yang digunakan untuk memperoleh aliran yang dapat ditulis untuk setiap halaman yang dirender."
type: docs
url: /id/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/
is_root: false
weight: 2010
---


## create_page_stream property

Delegate pembuatan aliran halaman yang digunakan untuk memperoleh aliran yang dapat ditulis untuk setiap halaman yang dirender.

GroupDocs.Watermark merender halaman dokumen sebagai gambar. Sediakan callable yang menerima nomor halaman (`int`) dan mengembalikan aliran `io.RawIOBase` yang dapat ditulisi; perpustakaan menulis gambar yang dirender ke aliran tersebut dan menutupnya.

### Definition:
```python
@property
def create_page_stream(self):
    ...
@create_page_stream.setter
def create_page_stream(self, value):
    ...
```

### Lihat Juga
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
