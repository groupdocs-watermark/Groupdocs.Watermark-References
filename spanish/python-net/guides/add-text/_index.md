---
title: "Agregar marcas de agua de texto"
linkTitle: "Add text watermarks"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Este artículo muestra cómo agregar una marca de agua de texto a un documento y guardar el resultado con GroupDocs.Watermark para Python a través de .NET."
type: docs
url: /es/python-net/guides/add-text/
is_root: false
weight: 40
---


Una de las principales características de GroupDocs.Watermark es agregar marcas de agua de texto a los documentos. Puedes agregar marcas de agua a documentos o imágenes desde una ruta local, así como desde un flujo. Para una lista completa de formatos compatibles, consulta [Supported document formats](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/).

## Add a text watermark

Para agregar una marca de agua de texto, sigue estos pasos:

1. Abre el documento pasando su ruta (o un flujo) a la clase [Watermarker](https://reference.groupdocs.com/watermark/python-net/) , usando un bloque `with` para que el documento se libere automáticamente.
2. Crea un [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) con el texto deseado y un [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/).
3. Estiliza la marca de agua — por ejemplo, establece `foreground_color` y la alineación.
4. Llama a `add()` para aplicar la marca de agua y a `save()` para escribir el resultado.

{{< tabs \"code-example-add-text\">}}
{{< tab \"add_text_watermark.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_text_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        # Construye la marca de agua de texto y estílela
        watermark = TextWatermark("Top Secret", Font("Arial", 36.0))
        watermark.foreground_color = Color.red
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER
        watermark.rotate_angle = 45.0
        watermark.opacity = 0.4

        watermarker.add(watermark)
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    add_text_watermark()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` es el archivo de ejemplo usado en este ejemplo. Haz clic [aquí](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-text/sample.pdf) para descargarlo.

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 313 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-text/add_text_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Ejecuta el programa. Aparece un nuevo documento con marca de agua en la ruta especificada.

## What's next

GroupDocs.Watermark ofrece muchas más capacidades para marcas de agua de texto — colores de fondo y de primer plano, fuentes personalizadas, opacidad, rotación, mosaico y posicionamiento absoluto o relativo. Consulta [Adding text watermarks](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/) en la guía avanzada.
