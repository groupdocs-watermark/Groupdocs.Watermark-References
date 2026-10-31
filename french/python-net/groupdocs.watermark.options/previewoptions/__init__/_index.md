---
title: "__init__ constructeur"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Initialise une nouvelle instance de PreviewOptions qui ferme le flux de sortie après utilisation."
type: docs
url: /fr/python-net/groupdocs.watermark.options/previewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Initialise une nouvelle instance de PreviewOptions qui ferme le flux de sortie après utilisation.

```python
def __init__(self, create_page_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable[[int], io.RawIOBase] – Crée un flux pour un aperçu de page spécifique. |

### Exemple

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # Fournissez un flux de fichier inscriptible pour chaque page à rendre
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

Initialise une nouvelle instance de PreviewOptions qui renvoie le flux de sortie au client pour une utilisation ultérieure.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable qui crée un flux pour un aperçu de page spécifique. Reçoit le numéro de page (`int`) et doit retourner un flux inscriptible (`io.RawIOBase`). |
| release_page_stream | `ReleasePageStream` | Callable qui est invoqué lorsque la génération de l'aperçu de page est terminée et fournit le flux de sortie. |

### Exemple

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # Fournissez un flux de fichier inscriptible pour chaque page à rendre
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

### Voir aussi
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
