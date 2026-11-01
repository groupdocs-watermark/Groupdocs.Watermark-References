---
title: "Vista previa del documento"
linkTitle: "Document preview"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Genere imágenes de vista previa (PNG/JPG/BMP) para las páginas del documento usando GroupDocs.Watermark para Python a través de .NET."
type: docs
url: /es/python-net/guides/preview/
is_root: false
weight: 110
---


GroupDocs.Watermark puede renderizar páginas de documentos como imágenes para que puedas mostrar miniaturas de página sin abrir completamente un documento en un visor. Controlas el renderizado con una función de devolución de llamada `create_page_stream` que proporciona un flujo de archivo escribible para cada página — la biblioteca escribe la imagen de la página en él y lo cierra por ti.

## Generate a document preview

Configura [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/) con una devolución de llamada `create_page_stream`, elige el `preview_format` y enumera los `page_numbers` a renderizar.

{{< tabs \"code-example-preview\">}}
{{< tab \"generate_preview.py\" >}}
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
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` es el archivo de ejemplo de dos páginas usado en este ejemplo. Haz clic [aquí](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/preview/sample.pdf) para descargarlo.

{{< /tab >}}
{{< tab \"generate-preview-outputs.zip\" >}}
```text
output-page-1.png (600 KB)
output-page-2.png (94 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/preview/generate_preview/generate-preview-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

Las imágenes de página se escriben en el directorio actual — un PNG por cada página solicitada. Usa `PreviewFormats.JPEG` o `PreviewFormats.BMP` para otros formatos, y establece `options.width` / `options.height` para controlar el tamaño renderizado.

La biblioteca cierra cada archivo que devuelve `create_page_stream` una vez que la página se ha escrito. Para actuar sobre una página tan pronto como esté lista, pasa una segunda devolución de llamada: `PreviewOptions(create_page_stream, release_page_stream)` llama a `release_page_stream(page_number, stream)` con el objeto `create_page_stream` devuelto para esa página, después de que la imagen completa esté en él. Un `release_page_stream(page_number)` de un solo argumento también funciona. `create_page_stream` también puede devolver un `io.BytesIO`: permanece abierto y mantiene la imagen de la página hasta que `release_page_stream` la recibe.

**Use case:** Generate page previews to display in a web app, dashboard, or document-management system without requiring users to download the full file.
