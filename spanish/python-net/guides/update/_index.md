---
title: "Actualizar marcas de agua"
linkTitle: "Update watermarks"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Buscar marcas de agua de texto o imagen existentes y actualizarlas usando GroupDocs.Watermark para Python a través de .NET."
type: docs
url: /es/python-net/guides/update/
is_root: false
weight: 90
---


Puede buscar marcas de agua existentes en un documento y modificarlas en el mismo lugar — por ejemplo, reemplazar el texto de una marca de agua de texto o intercambiar la imagen de una marca de agua de imagen.

## Update text watermarks

Busque una marca de agua por su contenido de texto y luego asigne un nuevo valor a cada coincidencia. El ejemplo a continuación abre un documento que ya contiene una marca de agua "CONFIDENTIAL" y la reemplaza por "APPROVED".

{{< tabs "code-example-update">}}
{{< tab "update_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def update_watermark():
    with Watermarker("./watermarked-document.pdf") as watermarker:
        # Encuentre las marcas de agua cuyo texto coincida con el criterio
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s).")
        for watermark in possible:
            try:
                watermark.text = "APPROVED"
            except Exception:
                # Algunas entidades encontradas no admiten edición de texto — omítalas
                pass
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    update_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.pdf" >}}

`watermarked-document.pdf` es el archivo de ejemplo utilizado en este caso. Haga clic [aquí](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/watermarked-document.pdf) para descargarlo.

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 444 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/update/update_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

## Update image watermarks

Las marcas de agua de imagen pueden encontrarse mediante hashing perceptual ([`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)) y actualizarse asignando nuevos bytes a `image_data`. El ejemplo a continuación encuentra la marca de agua del logotipo y la reemplaza por un sello "APPROVED":

{{< tabs "code-example-update-image">}}
{{< tab "update_image_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

def update_image_watermark():
    with Watermarker("./watermarked-document.docx") as watermarker:
        criteria = ImageDctHashSearchCriteria("./logo.png")
        criteria.max_difference = 0.9
        possible = watermarker.search(criteria)
        with open("./stamp.png", "rb") as f:
            image_data = f.read()
        for watermark in possible:
            try:
                watermark.image_data = image_data
            except Exception:
                # Algunas entidades encontradas no admiten edición de imágenes — omítelas
                pass
        watermarker.save("./output.docx")

if __name__ == "__main__":
    update_image_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.docx" >}}

`watermarked-document.docx`, `logo.png` y `stamp.png` son los archivos de muestra utilizados en este ejemplo. Descarga [watermarked-document.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/watermarked-document.docx), [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/logo.png) y [stamp.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/stamp.png).

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 19 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/update/update_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}
