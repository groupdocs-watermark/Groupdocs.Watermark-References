---
title: "PreviewOptions classe"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Fournit des options pour définir les exigences et les délégués de flux pour la génération d'aperçus."
type: docs
url: /fr/python-net/groupdocs.watermark.options/previewoptions/
is_root: false
weight: 60
---


## PreviewOptions class

Fournit des options pour définir les exigences et les délégués de flux pour la génération d'aperçus.

Le type PreviewOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream) | Initialise une nouvelle instance de PreviewOptions qui ferme le flux de sortie après utilisation. |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream-release_page_stream) | Initialise une nouvelle instance de PreviewOptions qui renvoie le flux de sortie au client pour une utilisation ultérieure. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [create_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/) | Le délégué de création du flux de page utilisé pour obtenir un flux en écriture pour chaque page rendue. |
| [height](/watermark/python-net/groupdocs.watermark.options/previewoptions/height/) | La hauteur de l'aperçu de page. |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options/previewoptions/page_numbers/) | Le tableau des numéros de page pour générer les aperçus. |
| [preview_format](/watermark/python-net/groupdocs.watermark.options/previewoptions/preview_format/) | Le format de l'image d'aperçu. |
| [release_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/release_page_stream/) | Le délégué de fin d'aperçu de page. |
| [width](/watermark/python-net/groupdocs.watermark.options/previewoptions/width/) | La largeur de l'aperçu de page. |

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

### Guides
Guides de tâches qui utilisent `PreviewOptions` :

* [Document preview](/watermark/python-net/guides/preview/)

### Voir aussi
* module [`groupdocs.watermark.options`](/watermark/python-net/groupdocs.watermark.options/)
