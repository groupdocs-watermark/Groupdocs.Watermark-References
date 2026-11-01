---
title: "save‑metod"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Sparar dokumentdata till den underliggande strömmen."
type: docs
url: /sv/python-net/groupdocs.watermark/watermarker/save/
is_root: false
weight: 1130
---


## save

Sparar dokumentdata till den underliggande strömmen.

Läs mer om att spara dokumenten: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self):
    ...
```

### Exempel

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

Sparar dokumentet till den angivna filplatsen.

Läs mer om att spara dokumenten: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | `str` | Filvägen där dokumentdata ska sparas. |

### Exempel

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

Sparar dokumentet till den angivna strömmen.

Läs mer om att spara dokumenten på https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, document):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| document | `io.RawIOBase` | Strömmen för att spara dokumentdata till. |

### Exempel

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
    # `stream` innehåller nu de sparade PDF-byterna
```

## save {#options}

Sparar dokumentdata till den underliggande strömmen med hjälp av sparalternativ.

Läs mer om att spara dokumenten.

```python
def save(self, options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | `SaveOptions` | Ytterligare alternativ att använda när ett dokument sparas. |

### Exempel

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

Sparar dokumentet till den angivna filplatsen med hjälp av sparalternativ.

Läs mer om att spara dokumenten: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path, options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | `str` | Filvägen där dokumentdata ska sparas. |
| options | `SaveOptions` | Ytterligare alternativ att använda när ett dokument sparas. |

### Exempel

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

Sparar dokumentet till den angivna strömmen med hjälp av sparalternativ

Läs mer om att spara dokumenten i GroupDocs-dokumentationen.

```python
def save(self, document, options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| document | `io.RawIOBase` | Strömmen för att spara dokumentdata till. |
| options | `SaveOptions` | Ytterligare alternativ att använda när ett dokument sparas. |

### Exempel

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
        # stream innehåller nu den sparade PDF-datan
        # t.ex., skriv till en fil
        with open("output.pdf", "wb") as f:
            f.write(stream.getvalue())

if __name__ == "__main__":
    add_watermark_and_save()
```

### Se även
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
