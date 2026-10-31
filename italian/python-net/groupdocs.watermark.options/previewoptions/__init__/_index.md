---
title: "__init__ costruttore"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Inizializza una nuova istanza di PreviewOptions che chiude lo stream di output dopo l'uso."
type: docs
url: /it/python-net/groupdocs.watermark.options/previewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Inizializza una nuova istanza di PreviewOptions che chiude lo stream di output dopo l'uso.

```python
def __init__(self, create_page_stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable[[int], io.RawIOBase] – Crea uno stream per l'anteprima di una pagina specifica. |

### Esempio

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # Fornisci un flusso di file scrivibile per ogni pagina da renderizzare
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```

## __init__ {#create_page_stream-release_page_stream}

Inizializza una nuova istanza di PreviewOptions che restituisce lo stream di output al client per un uso successivo.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable che crea uno stream per l'anteprima di una pagina specifica. Riceve il numero della pagina (`int`) e deve restituire uno stream scrivibile (`io.RawIOBase`). |
| release_page_stream | `ReleasePageStream` | Callable che viene invocato quando la generazione dell'anteprima della pagina è completata e fornisce lo stream di output. |

### Esempio

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # Fornisci un flusso di file scrivibile per ogni pagina da renderizzare
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```

### Vedi anche
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
