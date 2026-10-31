---
title: "metode save"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menyimpan data dokumen ke aliran dasar."
type: docs
url: /id/python-net/groupdocs.watermark/watermarker/save/
is_root: false
weight: 1130
---


## save

Menyimpan data dokumen ke aliran dasar.

Pelajari lebih lanjut tentang menyimpan dokumen: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self):
    ...
```

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker(r"D:\\test.msg") as watermarker:
    criteria = TextSearchCriteria("test", False)
    watermarks = watermarker.search(criteria)
    watermarker.remove(watermarks)
    watermarker.save()
```

## save {#file_path}

Menyimpan dokumen ke lokasi file yang ditentukan.

Pelajari lebih lanjut tentang menyimpan dokumen: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | `str` | Jalur file untuk menyimpan data dokumen. |

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font

def add_and_save():
    with Watermarker("input.pdf") as watermarker:
        watermark = TextWatermark("top secret", Font("Arial", 36))
        watermarker.add(watermark)
        watermarker.save("output.pdf")
```

## save {#document}

Menyimpan dokumen ke aliran yang ditentukan.

Pelajari lebih lanjut tentang menyimpan dokumen di https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, document):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| document | `io.RawIOBase` | Aliran untuk menyimpan data dokumen. |

### Contoh

```python
from io import BytesIO
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font

with Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    stream = BytesIO()
    watermarker.save(stream)
    # `stream` sekarang berisi byte PDF yang disimpan
```

## save {#options}

Menyimpan data dokumen ke aliran dasar menggunakan opsi penyimpanan.

Pelajari lebih lanjut tentang menyimpan dokumen.

```python
def save(self, options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | `SaveOptions` | Opsi tambahan yang dapat digunakan saat menyimpan dokumen. |

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import SaveOptions
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font

with Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    watermarker.save(SaveOptions())
```

## save {#file_path-options}

Menyimpan dokumen ke lokasi file yang ditentukan menggunakan opsi penyimpanan.

Pelajari lebih lanjut tentang menyimpan dokumen: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path, options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | `str` | Jalur file untuk menyimpan data dokumen. |
| options | `SaveOptions` | Opsi tambahan yang dapat digunakan saat menyimpan dokumen. |

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font
from groupdocs.watermark.options import SaveOptions

with Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    watermarker.save("output.pdf", SaveOptions())
```

## save {#document-options}

Menyimpan dokumen ke aliran yang ditentukan menggunakan opsi penyimpanan.

Pelajari lebih lanjut tentang menyimpan dokumen di dokumentasi GroupDocs.

```python
def save(self, document, options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| document | `io.RawIOBase` | Aliran untuk menyimpan data dokumen. |
| options | `SaveOptions` | Opsi tambahan yang dapat digunakan saat menyimpan dokumen. |

### Contoh

```python
from io import BytesIO
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import SaveOptions
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font

def add_watermark_and_save():
    with Watermarker("input.pdf") as watermarker:
        watermark = TextWatermark("top secret", Font("Arial", 36))
        watermarker.add(watermark)

        stream = BytesIO()
        watermarker.save(stream, SaveOptions())
        # stream sekarang berisi data PDF yang disimpan
        # misalnya, tulis ke file
        with open("output.pdf", "wb") as f:
            f.write(stream.getvalue())

if __name__ == "__main__":
    add_watermark_and_save()
```

### Lihat Juga
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
