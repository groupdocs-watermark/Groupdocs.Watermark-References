---
title: "Eliminar marcas de agua"
linkTitle: "Clear watermarks"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Buscar y eliminar marcas de agua de texto o imagen existentes usando GroupDocs.Watermark para Python a través de .NET."
type: docs
url: /es/python-net/guides/clear/
is_root: false
weight: 100
---


Puede buscar marcas de agua existentes en un documento y eliminarlas. El ejemplo a continuación encuentra una marca de agua de texto "CONFIDENTIAL" y la elimina, produciendo un documento limpio.

## Remove text watermarks

Itere los resultados de búsqueda en sentido inverso para que al eliminar un elemento no se desplacen los índices que aún quedan por visitar, y llame a `remove()` para cada coincidencia.

{{< tabs "code-example-clear">}}
{{< tab "clear_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def clear_watermark():
    with Watermarker("./watermarked-document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        # Eliminar en sentido inverso para que los índices permanezcan válidos a medida que se eliminan los elementos
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    clear_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.pdf" >}}

`watermarked-document.pdf` es el archivo de ejemplo utilizado en este caso. Haga clic [aquí](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/watermarked-document.pdf) para descargarlo.

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 360 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/clear/clear_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

**Use case:** Remove outdated labels such as "Draft" or "Internal Use Only" before sharing a document externally.

## Remove image watermarks

Las marcas de agua de imagen pueden encontrarse mediante hashing perceptual y eliminarse de la misma manera:

{{< tabs "code-example-clear-image">}}
{{< tab "clear_image_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

def clear_image_watermark():
    with Watermarker("./watermarked-document.docx") as watermarker:
        criteria = ImageDctHashSearchCriteria("./logo.png")
        criteria.max_difference = 0.9
        possible = watermarker.search(criteria)
        # Eliminar en sentido inverso para que los índices permanezcan válidos a medida que se eliminan los elementos
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.docx")

if __name__ == "__main__":
    clear_image_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.docx" >}}

`watermarked-document.docx` y `logo.png` son los archivos de ejemplo utilizados en este caso. Descargue [watermarked-document.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/watermarked-document.docx) y [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/logo.png).

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 13 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/clear/clear_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}
