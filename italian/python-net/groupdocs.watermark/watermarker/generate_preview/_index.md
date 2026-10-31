---
title: "metodo generate_preview"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Genera immagini di anteprima per il documento."
type: docs
url: /it/python-net/groupdocs.watermark/watermarker/generate_preview/
is_root: false
weight: 1040
---


## generate_preview {#preview_options}

Genera immagini di anteprima per il documento.

```python
def generate_preview(self, preview_options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| preview_options | `PreviewOptions` | Opzioni aggiuntive da utilizzare durante la generazione delle immagini di anteprima. |

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
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
