---
title: "méthode generate_preview"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Génère des images d'aperçu pour le document."
type: docs
url: /fr/python-net/groupdocs.watermark/watermarker/generate_preview/
is_root: false
weight: 1040
---


## generate_preview {#preview_options}

Génère des images d'aperçu pour le document.

```python
def generate_preview(self, preview_options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| preview_options | `PreviewOptions` | Options supplémentaires à utiliser lors de la génération d’images d’aperçu. |

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
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
