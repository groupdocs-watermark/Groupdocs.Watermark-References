---
title: "save-methode"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Slaat de documentgegevens op naar de onderliggende stream."
type: docs
url: /nl/python-net/groupdocs.watermark/watermarker/save/
is_root: false
weight: 1130
---


## save

Slaat de documentgegevens op naar de onderliggende stream.

Meer informatie over het opslaan van de documenten: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self):
    ...
```

### Voorbeeld

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

Slaat het document op naar de opgegeven bestandslocatie.

Meer informatie over het opslaan van de documenten: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | `str` | Het bestandspad om de documentgegevens op te slaan. |

### Voorbeeld

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

Slaat het document op naar de opgegeven stream.

Meer informatie over het opslaan van de documenten op https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, document):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| document | `io.RawIOBase` | De stream om de documentgegevens op te slaan. |

### Voorbeeld

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
    # `stream` bevat nu de opgeslagen PDF-bytes
```

## save {#options}

Slaat de documentgegevens op naar de onderliggende stream met behulp van opslagopties.

Meer informatie over het opslaan van de documenten.

```python
def save(self, options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | `SaveOptions` | Aanvullende opties om te gebruiken bij het opslaan van een document. |

### Voorbeeld

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

Slaat het document op naar de opgegeven bestandslocatie met behulp van opslagopties.

Meer informatie over het opslaan van de documenten: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path, options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | `str` | Het bestandspad om de documentgegevens op te slaan. |
| options | `SaveOptions` | Aanvullende opties om te gebruiken bij het opslaan van een document. |

### Voorbeeld

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

Slaat het document op naar de opgegeven stream met behulp van opslagopties.

Meer informatie over het opslaan van de documenten in de GroupDocs-documentatie.

```python
def save(self, document, options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| document | `io.RawIOBase` | De stream om de documentgegevens op te slaan. |
| options | `SaveOptions` | Aanvullende opties om te gebruiken bij het opslaan van een document. |

### Voorbeeld

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
        # stream bevat nu de opgeslagen PDF-gegevens
        # bijv., schrijf naar een bestand
        with open("output.pdf", "wb") as f:
            f.write(stream.getvalue())

if __name__ == "__main__":
    add_watermark_and_save()
```

### Zie ook
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
