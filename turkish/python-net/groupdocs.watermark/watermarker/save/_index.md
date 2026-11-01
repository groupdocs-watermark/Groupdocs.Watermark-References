---
title: "save metodu"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Belge verilerini temel akışa kaydeder."
type: docs
url: /tr/python-net/groupdocs.watermark/watermarker/save/
is_root: false
weight: 1130
---


## save

Belge verilerini temel akışa kaydeder.

Belgeleri kaydetme hakkında daha fazla bilgi edinin: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self):
    ...
```

### Örnek

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

Belgeyi belirtilen dosya konumuna kaydeder.

Belgeleri kaydetme hakkında daha fazla bilgi edinin: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | `str` | Belge verilerinin kaydedileceği dosya yolu. |

### Örnek

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

Belgeyi belirtilen akışa kaydeder.

https://docs.groupdocs.com/display/watermarknet/Saving+documents adresindeki belgeleri kaydetme hakkında daha fazla bilgi edinin.

```python
def save(self, document):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| document | `io.RawIOBase` | Belge verilerinin kaydedileceği akış. |

### Örnek

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
    # `stream` artık kaydedilmiş PDF baytlarını içeriyor
```

## save {#options}

Belge verilerini kaydetme seçeneklerini kullanarak temel akışa kaydeder.

Belgeleri kaydetme hakkında daha fazla bilgi edinin.

```python
def save(self, options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | `SaveOptions` | Bir belgeyi kaydederken kullanılacak ek seçenekler. |

### Örnek

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

Belgeyi kaydetme seçeneklerini kullanarak belirtilen dosya konumuna kaydeder.

Belgeleri kaydetme hakkında daha fazla bilgi edinin: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path, options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | `str` | Belge verilerinin kaydedileceği dosya yolu. |
| options | `SaveOptions` | Bir belgeyi kaydederken kullanılacak ek seçenekler. |

### Örnek

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

Belgeyi kaydetme seçeneklerini kullanarak belirtilen akışa kaydeder.

GroupDocs belgelerinde belgeleri kaydetme hakkında daha fazla bilgi edinin.

```python
def save(self, document, options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| document | `io.RawIOBase` | Belge verilerinin kaydedileceği akış. |
| options | `SaveOptions` | Bir belgeyi kaydederken kullanılacak ek seçenekler. |

### Örnek

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
        # akış artık kaydedilmiş PDF verilerini içeriyor
        # ör., bir dosyaya yazma
        with open("output.pdf", "wb") as f:
            f.write(stream.getvalue())

if __name__ == "__main__":
    add_watermark_and_save()
```

### Ayrıca Bakınız
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
