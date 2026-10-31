---
title: "Ajouter des filigranes d'image"
linkTitle: "Add image watermarks"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Cet article montre comment ajouter un filigrane d'image à un document et enregistrer le résultat avec GroupDocs.Watermark pour Python via .NET."
type: docs
url: /fr/python-net/guides/add-image/
is_root: false
weight: 50
---


Une des principales fonctionnalités de GroupDocs.Watermark est l'ajout de filigranes d'image aux documents. Vous pouvez ajouter des filigranes aux documents ou aux images depuis un chemin local, ainsi que depuis un flux. Pour une liste complète des formats pris en charge, consultez [Formats de documents pris en charge](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/).

## Add an image watermark

Pour ajouter un filigrane d'image, suivez ces étapes :

1. Ouvrez le document en passant son chemin (ou un flux) à la classe [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/).
2. Créez un [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) à partir du fichier d'image du filigrane (ou d'un flux).
3. Positionnez le filigrane — par exemple, définissez `horizontal_alignment`, `vertical_alignment` et `opacity`.
4. Appelez `add()` pour appliquer le filigrane et `save()` pour enregistrer le résultat.

{{< tabs "code-example-add-image">}}
{{< tab "add_image_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_image_watermark():
    with Watermarker("./sample.docx") as watermarker:
        # Créez un filigrane d'image à partir d'un fichier logo et centrez-le
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
{{< tab "sample.docx" >}}

`sample.docx` et `logo.png` sont les fichiers d'exemple utilisés dans cet exemple. Téléchargez [sample.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/sample.docx) et [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/logo.png).

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 127 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-image/add_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}

## What's next

GroupDocs.Watermark offre davantage de fonctionnalités pour les filigranes d'image — chargement depuis des flux, mise à l'échelle, mosaïquage et positionnement absolu ou relatif. Voir [Ajout de filigranes d'image](https://docs.groupdocs.com/watermark/python-net/adding-image-watermarks/) dans le guide avancé.
