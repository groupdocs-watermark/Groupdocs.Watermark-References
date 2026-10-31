---
title: "Classe PreviewOptions"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Fornisce opzioni per impostare requisiti e delegati di stream per la generazione dell'anteprima."
type: docs
url: /it/python-net/groupdocs.watermark.options/previewoptions/
is_root: false
weight: 60
---


## PreviewOptions class

Fornisce opzioni per impostare requisiti e delegati di stream per la generazione dell'anteprima.

Il tipo PreviewOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream) | Inizializza una nuova istanza di PreviewOptions che chiude lo stream di output dopo l'uso. |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream-release_page_stream) | Inizializza una nuova istanza di PreviewOptions che restituisce lo stream di output al client per un uso successivo. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [create_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/) | Il delegato di creazione dello stream di pagina usato per ottenere uno stream scrivibile per ogni pagina renderizzata. |
| [height](/watermark/python-net/groupdocs.watermark.options/previewoptions/height/) | L'altezza dell'anteprima della pagina. |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options/previewoptions/page_numbers/) | L'array di numeri di pagina per generare le anteprime. |
| [preview_format](/watermark/python-net/groupdocs.watermark.options/previewoptions/preview_format/) | Il formato dell'immagine di anteprima. |
| [release_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/release_page_stream/) | Il delegato di completamento dell'anteprima della pagina. |
| [width](/watermark/python-net/groupdocs.watermark.options/previewoptions/width/) | La larghezza dell'anteprima della pagina. |

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

### Guides
Guide operative che utilizzano `PreviewOptions`:

* [Document preview](/watermark/python-net/guides/preview/)

### Vedi anche
* module [`groupdocs.watermark.options`](/watermark/python-net/groupdocs.watermark.options/)
