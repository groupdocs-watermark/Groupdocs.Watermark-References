---
title: "__init__ konstruktor"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menginisialisasi instance Watermarker baru dengan jalur dokumen yang ditentukan dan opsi pemuatan."
type: docs
url: /id/python-net/groupdocs.watermark/watermarker/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Menginisialisasi instance Watermarker baru dengan jalur dokumen yang ditentukan dan opsi pemuatan.

Pelajari lebih lanjut tentang memuat dokumen: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | `str` | Jalur file untuk memuat dokumen dari. |

| Menaikkan | Deskripsi |
| :- | :- |
| `UnsupportedFileTypeException` | Jenis dokumen yang diberikan tidak didukung. |
| `InvalidPasswordException` | Kata sandi yang diberikan tidak benar. |

### Contoh

```python
from groupdocs.watermark import Watermarker

# Muat sebuah dokumen.
watermarker = Watermarker("./document.pdf")
# Gunakan metode Watermarker untuk menambahkan, mencari, atau menghapus watermark.

# Simpan dokumen.
watermarker.save("./output.pdf")
```

## __init__ {#file_path-options}

Menginisialisasi Watermarker dengan jalur dokumen yang ditentukan dan pengaturan.

Pelajari lebih lanjut tentang memuat dokumen: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | `str` | Jalur file untuk memuat dokumen dari. |
| options | `LoadOptions` | Opsi tambahan untuk digunakan saat memuat dokumen. |

| Menaikkan | Deskripsi |
| :- | :- |
| `UnsupportedFileTypeException` | Jenis dokumen yang diberikan tidak didukung. |
| `InvalidPasswordException` | Kata sandi yang diberikan tidak benar. |

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

load_options = PdfLoadOptions()
load_options.password = "123"

with Watermarker(r"C:\Documents\test.pdf", load_options) as watermarker:
    # lakukan operasi pada PDF terenkripsi
    pass
```

## __init__ {#file_path-settings}

Menginisialisasi instance Watermarker baru dengan jalur dokumen yang ditentukan, opsi pemuatan, dan pengaturan.

Pelajari lebih lanjut tentang memuat dokumen: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, settings):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | `str` | Jalur file untuk memuat dokumen dari. |
| settings | `WatermarkerSettings` | Pengaturan tambahan untuk digunakan saat bekerja dengan dokumen yang dimuat. |

| Menaikkan | Deskripsi |
| :- | :- |
| `UnsupportedFileTypeException` | Jenis dokumen yang diberikan tidak didukung. |
| `InvalidPasswordException` | Kata sandi yang diberikan tidak benar. |

### Contoh

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.search.objects import SearchableObjects
from groupdocs.watermark.search.objects import WordProcessingSearchableObjects, SpreadsheetSearchableObjects, PresentationSearchableObjects, DiagramSearchableObjects, PdfSearchableObjects

settings = WatermarkerSettings()
settings.searchable_objects = SearchableObjects(
    word_processing_searchable_objects=WordProcessingSearchableObjects.HYPERLINKS
                     | WordProcessingSearchableObjects.TEXT,
    spreadsheet_searchable_objects=SpreadsheetSearchableObjects.HEADERS_FOOTERS,
    presentation_searchable_objects=PresentationSearchableObjects.SLIDES_BACKGROUNDS
                  | PresentationSearchableObjects.SHAPES,
    diagram_searchable_objects=DiagramSearchableObjects.NONE,
    pdf_searchable_objects=PdfSearchableObjects.ALL,
)

with Watermarker("./document.pdf", settings) as watermarker:
    # bekerja dengan watermarker, mis., mencari atau menghapus watermark
    pass
```

## __init__ {#file_path-options-settings}

Menginisialisasi sebuah instance baru dari kelas Watermarker dengan aliran yang ditentukan.

Pelajari lebih lanjut tentang memuat dokumen: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options, settings):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | `str` | Jalur file untuk memuat dokumen dari. |
| options | `LoadOptions` | Opsi tambahan untuk digunakan saat memuat dokumen. |
| settings | `WatermarkerSettings` | Pengaturan tambahan untuk digunakan saat bekerja dengan dokumen yang dimuat. |

| Menaikkan | Deskripsi |
| :- | :- |
| `UnsupportedFileTypeException` | Jenis dokumen yang diberikan tidak didukung. |
| `InvalidPasswordException` | Kata sandi yang diberikan tidak benar. |

### Contoh

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.options.email import EmailLoadOptions
from groupdocs.watermark.search.search_criteria import TextSearchCriteria
from groupdocs.watermark.search.objects import SearchableObjects, EmailSearchableObjects

def search_email():
    settings = WatermarkerSettings()
    settings.searchable_objects = SearchableObjects(
        email_searchable_objects=(
            EmailSearchableObjects.Subject
            | EmailSearchableObjects.HtmlBody
            | EmailSearchableObjects.PlainTextBody
        )
    )
    load_options = EmailLoadOptions()
    with Watermarker("./test.msg", load_options, settings) as watermarker:
        criteria = TextSearchCriteria("test", False)
        watermarks = watermarker.search(criteria)
        watermarks.clear()
        watermarker.save()
```

## __init__ {#document}

Menginisialisasi instance Watermarker baru dengan aliran yang ditentukan dan opsi pemuatan.

Pelajari lebih lanjut tentang memuat dokumen: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| document | `io.RawIOBase` | Aliran untuk memuat dokumen dari. |

| Menaikkan | Deskripsi |
| :- | :- |
| `UnsupportedFileTypeException` | Jenis dokumen yang diberikan tidak didukung. |
| `InvalidPasswordException` | Kata sandi yang diberikan tidak benar. |

### Contoh

```python
from groupdocs.watermark import Watermarker

def load_from_stream():
    with open("input.pdf", "rb") as input_stream, open("output.pdf", "wb") as output_stream:
        with Watermarker(input_stream) as watermarker:
            # Gunakan metode Watermarker untuk menambahkan, mencari atau menghapus watermark.
            watermarker.save(output_stream)
```

## __init__ {#document-options}

Menginisialisasi instance Watermarker baru dengan aliran yang ditentukan dan pengaturan.

Pelajari lebih lanjut tentang memuat dokumen.

```python
def __init__(self, document, options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| document | `io.RawIOBase` | Aliran untuk memuat dokumen dari. |
| options | `LoadOptions` | Opsi tambahan untuk digunakan saat memuat dokumen. |

| Menaikkan | Deskripsi |
| :- | :- |
| `UnsupportedFileTypeException` | Jenis dokumen yang diberikan tidak didukung. |
| `InvalidPasswordException` | Kata sandi yang diberikan tidak benar. |

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

with open(r"C:\Documents\test.pdf", "rb") as file_stream:
    load_options = PdfLoadOptions()
    load_options.password = "123"
    with Watermarker(file_stream, load_options) as watermarker:
        # lakukan operasi dengan watermarker
        pass
```

## __init__ {#document-settings}

Menginisialisasi sebuah instance baru dari kelas [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) dengan aliran yang ditentukan, opsi pemuatan, dan pengaturan.

Pelajari lebih lanjut tentang memuat dokumen.

```python
def __init__(self, document, settings):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| document | `io.RawIOBase` | Aliran untuk memuat dokumen dari. |
| settings | `WatermarkerSettings` | Pengaturan tambahan untuk digunakan saat bekerja dengan dokumen yang dimuat. |

| Menaikkan | Deskripsi |
| :- | :- |
| `UnsupportedFileTypeException` | Jenis dokumen yang diberikan tidak didukung. |
| `InvalidPasswordException` | Kata sandi yang diberikan tidak benar. |

### Contoh

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.search.objects import SearchableObjects
from groupdocs.watermark.search.objects import WordProcessingSearchableObjects, SpreadsheetSearchableObjects, PresentationSearchableObjects, DiagramSearchableObjects, PdfSearchableObjects

settings = WatermarkerSettings()
settings.searchable_objects = SearchableObjects(
    word_processing_searchable_objects=WordProcessingSearchableObjects.HYPERLINKS | WordProcessingSearchableObjects.TEXT,
    spreadsheet_searchable_objects=SpreadsheetSearchableObjects.HEADERS_FOOTERS,
    presentation_searchable_objects=PresentationSearchableObjects.SLIDES_BACKGROUNDS | PresentationSearchableObjects.SHAPES,
    diagram_searchable_objects=DiagramSearchableObjects.NONE,
    pdf_searchable_objects=PdfSearchableObjects.ALL,
)

for file_path in ["./document1.pdf", "./document2.docx"]:
    with open(file_path, "rb") as stream:
        with Watermarker(stream, settings) as watermarker:
            watermarks = watermarker.search()
            # bekerja dengan watermark yang ditemukan
```

## __init__ {#document-options-settings}

Menambahkan watermark ke dokumen yang dimuat.

Pelajari lebih lanjut tentang memuat dokumen di https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document, options, settings):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| document | `io.RawIOBase` | Aliran untuk memuat dokumen dari. |
| options | `LoadOptions` | Opsi tambahan untuk digunakan saat memuat dokumen. |
| settings | `WatermarkerSettings` | Pengaturan tambahan untuk digunakan saat bekerja dengan dokumen yang dimuat. |

| Menaikkan | Deskripsi |
| :- | :- |
| `UnsupportedFileTypeException` | Jenis dokumen yang diberikan tidak didukung. |
| `InvalidPasswordException` | Kata sandi yang diberikan tidak benar. |

### Contoh

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.options.email import EmailLoadOptions
from groupdocs.watermark.search.objects import SearchableObjects, EmailSearchableObjects
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

settings = WatermarkerSettings()
settings.searchable_objects = SearchableObjects(
    email_searchable_objects=(
        EmailSearchableObjects.Subject
        | EmailSearchableObjects.HtmlBody
        | EmailSearchableObjects.PlainTextBody
    )
)

load_options = EmailLoadOptions()
with open("./test.msg", "rb") as stream:
    with Watermarker(stream, load_options, settings) as watermarker:
        criteria = TextSearchCriteria("test", False)
        watermarks = watermarker.search(criteria)
        watermarks.clear()
        watermarker.save("./output.msg")
```

### Lihat Juga
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
