---
title: "¡Hola, Mundo!"
linkTitle: "Hello, World!"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Comienza rápidamente con GroupDocs.Watermark para Python a través de .NET creando y ejecutando un ejemplo sencillo."
type: docs
url: /es/python-net/guides/hello-world/
is_root: false
weight: 20
---


## Introduction
Un ejemplo de "Hello, World!" suele ser el primer paso al explorar GroupDocs.Watermark para Python a través de .NET. Sirve como una prueba simple para confirmar que tu entorno de desarrollo está configurado correctamente y que la biblioteca funciona como se espera.

## Overview
GroupDocs.Watermark para Python a través de .NET te permite agregar, buscar y eliminar marcas de agua en varios formatos de documento. Una amplia gama de [supported formats](https://docs.groupdocs.com/watermark/python-net/getting-started/supported-document-formats/) lo hace versátil para diferentes casos de uso.

## How to add a watermark
Los siguientes pasos demuestran cómo agregar una marca de agua de texto a un documento usando GroupDocs.Watermark para Python a través de .NET:

1. Importa las clases `groupdocs.watermark` que necesitas.
2. Abre un [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) con la ruta al documento de ejemplo.
3. Crea un [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) con el texto y la fuente deseados, y dale estilo.
4. Aplica la marca de agua con `add()`.
5. Guarda el resultado.

## Complete example
El ejemplo a continuación agrega una marca de agua de texto semi-transparente y diagonal "Hello, Watermark!" y guarda el resultado:

{{< tabs "code-example-hello-world" >}}
{{< tab "hello_world.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

def hello_world():
    # Abre el documento, agrega una única marca de agua de texto y guarda el resultado
    with Watermarker("./sample.pdf") as watermarker:
        watermark = TextWatermark("Hello, Watermark!", Font("Arial", 36.0))
        watermark.foreground_color = Color.red
        watermark.opacity = 0.5
        watermark.rotate_angle = 45.0
        watermarker.add(watermark)
        watermarker.save("./output.pdf")

    print("Watermark added successfully. Output saved to ./output.pdf.")

if __name__ == "__main__":
    hello_world()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` es el archivo de ejemplo utilizado en este caso. Haz clic [aquí](https://docs.groupdocs.com/watermark/python-net/_sample_files/getting-started/hello-world/sample.pdf) para descargarlo.

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 315 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/getting-started/hello-world/hello_world/output.pdf)
{{< /tab >}}
{{< /tabs >}}

La marca de agua se guarda nuevamente en el mismo formato PDF que `output.pdf`. Para estampar un documento diferente, cambia la ruta de entrada y la extensión de salida — GroupDocs.Watermark guarda en el formato del documento de entrada.

## Additional resources
Esta demostración hace referencia a los [ejemplos de código](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET/) de GroupDocs.Watermark para Python a través de .NET.
