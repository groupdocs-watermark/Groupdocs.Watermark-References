---
title: "Agregar marcas de agua de imagen"
linkTitle: "Add image watermarks"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Este artículo muestra cómo agregar una marca de agua de imagen a un documento y guardar el resultado con GroupDocs.Watermark para Python a través de .NET."
type: docs
url: /es/python-net/guides/add-image/
is_root: false
weight: 50
---


Una de las principales características de GroupDocs.Watermark es agregar marcas de agua de imagen a los documentos. Puedes agregar marcas de agua a documentos o imágenes desde una ruta local, así como desde un flujo. Para obtener una lista completa de los formatos compatibles, consulta [Formatos de documento compatibles](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/).

## Add an image watermark

Para agregar una marca de agua de imagen, sigue estos pasos:

1. Abre el documento pasando su ruta (o un flujo) a la clase [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/).
2. Crea un [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) a partir del archivo de imagen de la marca de agua (o un flujo).
3. Posiciona la marca de agua — por ejemplo, establece `horizontal_alignment`, `vertical_alignment` y `opacity`.
4. Llama a `add()` para aplicar la marca de agua y a `save()` para escribir el resultado.

{{< tabs \"code-example-add-image\">}}
{{< tab \"add_image_watermark.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_image_watermark():
    with Watermarker("./sample.docx") as watermarker:
        # Crear una marca de agua de imagen a partir de un archivo de logotipo y centrarla
        watermark = ImageWatermark("./logo.png")
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER
        watermark.opacity = 0.7

        watermarker.add(watermark)
        watermarker.save("./output.docx")

if __name__ == "__main__":
    add_image_watermark()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` y `logo.png` son los archivos de ejemplo utilizados en este caso. Descarga [sample.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/sample.docx) y [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/logo.png).

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 127 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-image/add_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}

## What's next

GroupDocs.Watermark ofrece más capacidades para marcas de agua de imagen — carga desde flujos, escalado, mosaico y posicionamiento absoluto o relativo. Consulta [Agregar marcas de agua de imagen](https://docs.groupdocs.com/watermark/python-net/adding-image-watermarks/) en la guía avanzada.
