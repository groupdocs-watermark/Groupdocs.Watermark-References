---
title: "método generate_preview"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Genera imágenes de vista previa para el documento."
type: docs
url: /es/python-net/groupdocs.watermark/watermarker/generate_preview/
is_root: false
weight: 1040
---


## generate_preview {#preview_options}

Genera imágenes de vista previa para el documento.

```python
def generate_preview(self, preview_options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| preview_options | `PreviewOptions` | Opciones adicionales para usar al generar imágenes de vista previa. |

### Ejemplo

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.options import PreviewOptions, PreviewFormats

    def generate_preview():
        # Proporcione un flujo de archivo escribible para cada página a renderizar
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

### Ver también
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
