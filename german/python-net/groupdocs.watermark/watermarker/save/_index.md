---
title: "Methode save"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Speichert die Dokumentdaten im zugrunde liegenden Stream."
type: docs
url: /de/python-net/groupdocs.watermark/watermarker/save/
is_root: false
weight: 1130
---


## save

Speichert die Dokumentdaten im zugrunde liegenden Stream.

Erfahren Sie mehr über das Speichern von Dokumenten: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self):
    ...
```

### Beispiel

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

Speichert das Dokument am angegebenen Dateipfad.

Erfahren Sie mehr über das Speichern von Dokumenten: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | `str` | Der Dateipfad, in dem die Dokumentdaten gespeichert werden sollen. |

### Beispiel

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

Speichert das Dokument im angegebenen Stream.

Erfahren Sie mehr über das Speichern von Dokumenten unter https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, document):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| document | `io.RawIOBase` | Der Stream, in dem die Dokumentdaten gespeichert werden sollen. |

### Beispiel

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
    # `stream` enthält jetzt die gespeicherten PDF‑Bytes
```

## save {#options}

Speichert die Dokumentdaten im zugrunde liegenden Stream unter Verwendung von Speicheroptionen.

Erfahren Sie mehr über das Speichern von Dokumenten.

```python
def save(self, options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | `SaveOptions` | Zusätzliche Optionen, die beim Speichern eines Dokuments verwendet werden können. |

### Beispiel

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

Speichert das Dokument am angegebenen Dateipfad unter Verwendung von Speicheroptionen.

Erfahren Sie mehr über das Speichern von Dokumenten: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path, options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | `str` | Der Dateipfad, in dem die Dokumentdaten gespeichert werden sollen. |
| options | `SaveOptions` | Zusätzliche Optionen, die beim Speichern eines Dokuments verwendet werden können. |

### Beispiel

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

Speichert das Dokument im angegebenen Stream unter Verwendung von Speicheroptionen.

Erfahren Sie mehr über das Speichern von Dokumenten in der GroupDocs-Dokumentation.

```python
def save(self, document, options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| document | `io.RawIOBase` | Der Stream, in dem die Dokumentdaten gespeichert werden sollen. |
| options | `SaveOptions` | Zusätzliche Optionen, die beim Speichern eines Dokuments verwendet werden können. |

### Beispiel

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
        # stream enthält jetzt die gespeicherten PDF‑Daten
        # z. B. in eine Datei schreiben
        with open("output.pdf", "wb") as f:
            f.write(stream.getvalue())

if __name__ == "__main__":
    add_watermark_and_save()
```

### Siehe auch
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
