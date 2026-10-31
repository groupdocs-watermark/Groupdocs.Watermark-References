---
title: "metodo save"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Salva i dati del documento nello stream sottostante."
type: docs
url: /it/python-net/groupdocs.watermark/watermarker/save/
is_root: false
weight: 1130
---


## save

Salva i dati del documento nello stream sottostante.

Maggiori informazioni sul salvataggio dei documenti: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self):
    ...
```

### Esempio

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

Salva il documento nella posizione file specificata.

Maggiori informazioni sul salvataggio dei documenti: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | `str` | Il percorso file in cui salvare i dati del documento. |

### Esempio

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

Salva il documento nello stream specificato.

Maggiori informazioni sul salvataggio dei documenti su https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, document):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| document | `io.RawIOBase` | Il flusso in cui salvare i dati del documento. |

### Esempio

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
    # `stream` ora contiene i byte PDF salvati
```

## save {#options}

Salva i dati del documento nello stream sottostante usando le opzioni di salvataggio.

Maggiori informazioni sul salvataggio dei documenti.

```python
def save(self, options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | `SaveOptions` | Opzioni aggiuntive da utilizzare durante il salvataggio di un documento. |

### Esempio

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

Salva il documento nella posizione file specificata usando le opzioni di salvataggio.

Maggiori informazioni sul salvataggio dei documenti: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path, options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | `str` | Il percorso file in cui salvare i dati del documento. |
| options | `SaveOptions` | Opzioni aggiuntive da utilizzare durante il salvataggio di un documento. |

### Esempio

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

Salva il documento nello stream specificato usando le opzioni di salvataggio.

Maggiori informazioni sul salvataggio dei documenti nella documentazione di GroupDocs.

```python
def save(self, document, options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| document | `io.RawIOBase` | Il flusso in cui salvare i dati del documento. |
| options | `SaveOptions` | Opzioni aggiuntive da utilizzare durante il salvataggio di un documento. |

### Esempio

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
        # stream ora contiene i dati PDF salvati
        # ad esempio, scrivi su un file
        with open("output.pdf", "wb") as f:
            f.write(stream.getvalue())

if __name__ == "__main__":
    add_watermark_and_save()
```

### Vedi anche
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
