---
title: "__init__ yapıcı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Belirtilen belge yoluyla yeni bir Watermarker örneği başlatır."
type: docs
url: /tr/python-net/groupdocs.watermark/watermarker/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Belirtilen belge yoluyla yeni bir Watermarker örneği başlatır.

Belgeleri yükleme hakkında daha fazla bilgi edinin: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | `str` | Belgeyi yüklemek için dosya yolu. |

| Yükseltir | Açıklama |
| :- | :- |
| `UnsupportedFileTypeException` | Sağlanan belge türü desteklenmiyor. |
| `InvalidPasswordException` | Sağlanan şifre yanlış. |

### Örnek

```python
from groupdocs.watermark import Watermarker

# Bir belge yükleyin.
watermarker = Watermarker("./document.pdf")
# Su işaretlerini eklemek, aramak veya kaldırmak için Watermarker yöntemlerini kullanın.

# Belgeyi kaydedin.
watermarker.save("./output.pdf")
```

## __init__ {#file_path-options}

Belirtilen belge yolu ve yükleme seçenekleriyle yeni bir Watermarker örneği başlatır.

Belgeleri yükleme hakkında daha fazla bilgi edinin: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | `str` | Belgeyi yüklemek için dosya yolu. |
| options | `LoadOptions` | Bir belge yüklerken kullanılacak ek seçenekler. |

| Yükseltir | Açıklama |
| :- | :- |
| `UnsupportedFileTypeException` | Sağlanan belge türü desteklenmiyor. |
| `InvalidPasswordException` | Sağlanan şifre yanlış. |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

load_options = PdfLoadOptions()
load_options.password = "123"

with Watermarker(r"C:\Documents\test.pdf", load_options) as watermarker:
    # Şifreli PDF üzerinde işlemler gerçekleştirin
    pass
```

## __init__ {#file_path-settings}

Belirtilen belge yolu ve ayarlarla bir Watermarker başlatır.

Belgeleri yükleme hakkında daha fazla bilgi edinin: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, settings):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | `str` | Belgeyi yüklemek için dosya yolu. |
| settings | `WatermarkerSettings` | Yüklenen belgeyle çalışırken kullanılacak ek ayarlar. |

| Yükseltir | Açıklama |
| :- | :- |
| `UnsupportedFileTypeException` | Sağlanan belge türü desteklenmiyor. |
| `InvalidPasswordException` | Sağlanan şifre yanlış. |

### Örnek

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
    # watermarker ile çalışın, ör. su işaretlerini arama veya kaldırma
    pass
```

## __init__ {#file_path-options-settings}

Belirtilen belge yolu, yükleme seçenekleri ve ayarlarla yeni bir Watermarker örneği başlatır.

Belgeleri yükleme hakkında daha fazla bilgi edinin: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options, settings):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | `str` | Belgeyi yüklemek için dosya yolu. |
| options | `LoadOptions` | Bir belge yüklerken kullanılacak ek seçenekler. |
| settings | `WatermarkerSettings` | Yüklenmiş belgeyle çalışırken kullanılacak ek ayarlar. |

| Yükseltir | Açıklama |
| :- | :- |
| `UnsupportedFileTypeException` | Sağlanan belge türü desteklenmiyor. |
| `InvalidPasswordException` | Sağlanan şifre yanlış. |

### Örnek

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

Belirtilen akışla Watermarker sınıfının yeni bir örneğini başlatır.

Belgeleri yükleme hakkında daha fazla bilgi edinin: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| document | `io.RawIOBase` | Belgeyi yüklemek için akış. |

| Yükseltir | Açıklama |
| :- | :- |
| `UnsupportedFileTypeException` | Sağlanan belge türü desteklenmiyor. |
| `InvalidPasswordException` | Sağlanan şifre yanlış. |

### Örnek

```python
from groupdocs.watermark import Watermarker

def load_from_stream():
    with open("input.pdf", "rb") as input_stream, open("output.pdf", "wb") as output_stream:
        with Watermarker(input_stream) as watermarker:
            # Su işaretlerini eklemek, aramak veya kaldırmak için Watermarker yöntemlerini kullanın.
            watermarker.save(output_stream)
```

## __init__ {#document-options}

Belirtilen akış ve yükleme seçenekleriyle yeni bir Watermarker örneği başlatır.

Belgeleri yükleme hakkında daha fazla bilgi edinin.

```python
def __init__(self, document, options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| document | `io.RawIOBase` | Belgeyi yüklemek için akış. |
| options | `LoadOptions` | Bir belge yüklerken kullanılacak ek seçenekler. |

| Yükseltir | Açıklama |
| :- | :- |
| `UnsupportedFileTypeException` | Sağlanan belge türü desteklenmiyor. |
| `InvalidPasswordException` | Sağlanan şifre yanlış. |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

with open(r"C:\Documents\test.pdf", "rb") as file_stream:
    load_options = PdfLoadOptions()
    load_options.password = "123"
    with Watermarker(file_stream, load_options) as watermarker:
        # watermarker ile işlemler gerçekleştirin
        pass
```

## __init__ {#document-settings}

Belirtilen akış ve ayarlarla yeni bir Watermarker örneği başlatır.

Belgeleri yükleme hakkında daha fazla bilgi edinin.

```python
def __init__(self, document, settings):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| document | `io.RawIOBase` | Belgeyi yüklemek için akış. |
| settings | `WatermarkerSettings` | Yüklenmiş belgeyle çalışırken kullanılacak ek ayarlar. |

| Yükseltir | Açıklama |
| :- | :- |
| `UnsupportedFileTypeException` | Sağlanan belge türü desteklenmiyor. |
| `InvalidPasswordException` | Sağlanan şifre yanlış. |

### Örnek

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
            # bulunan su işaretleriyle çalışın
```

## __init__ {#document-options-settings}

Belirtilen akış, yükleme seçenekleri ve ayarlarla yeni bir [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) sınıfının örneğini başlatır.

https://docs.groupdocs.com/display/watermarknet/Loading+documents adresinde belgeleri yükleme hakkında daha fazla bilgi edinin.

```python
def __init__(self, document, options, settings):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| document | `io.RawIOBase` | Belgeyi yüklemek için akış. |
| options | `LoadOptions` | Bir belge yüklerken kullanılacak ek seçenekler. |
| settings | `WatermarkerSettings` | Yüklenen belgeyle çalışırken kullanılacak ek ayarlar. |

| Yükseltir | Açıklama |
| :- | :- |
| `UnsupportedFileTypeException` | Sağlanan belge türü desteklenmiyor. |
| `InvalidPasswordException` | Sağlanan şifre yanlış. |

### Örnek

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

### Ayrıca Bakınız
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
