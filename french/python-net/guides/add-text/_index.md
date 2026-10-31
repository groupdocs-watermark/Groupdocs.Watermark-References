---
title: "Ajouter des filigranes texte"
linkTitle: "Add text watermarks"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Cet article montre comment ajouter un filigrane texte à un document et enregistrer le résultat avec GroupDocs.Watermark pour Python via .NET."
type: docs
url: /fr/python-net/guides/add-text/
is_root: false
weight: 40
---


L'une des principales fonctionnalités de GroupDocs.Watermark est l'ajout de filigranes texte aux documents. Vous pouvez ajouter des filigranes aux documents ou aux images depuis un chemin local, ainsi que depuis un flux. Pour la liste complète des formats pris en charge, consultez [Supported document formats](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/).

## Add a text watermark

Pour ajouter un filigrane texte, suivez ces étapes :

1. Ouvrez le document en passant son chemin (ou un flux) à la classe [Watermarker](https://reference.groupdocs.com/watermark/python-net/) , en utilisant un bloc `with` afin que le document soit libéré automatiquement.
2. Créez un [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) avec le texte souhaité et un [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/).
3. Stylisez le filigrane — par exemple, définissez `foreground_color` et l'alignement.
4. Appelez `add()` pour appliquer le filigrane et `save()` pour enregistrer le résultat.

{{< tabs "code-example-add-text">}}
{{< tab "add_text_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_text_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        # Construisez le filigrane texte et stylisez-le
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

`sample.pdf` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-text/sample.pdf) pour le télécharger.

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 313 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-text/add_text_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Exécutez le programme. Un nouveau document filigrané apparaît au chemin spécifié.

## What's next

GroupDocs.Watermark offre de nombreuses autres possibilités pour les filigranes texte — couleurs d'arrière-plan et de premier plan, polices personnalisées, opacité, rotation, mosaïque, et positionnement absolu ou relatif. Voir [Adding text watermarks](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/) dans le guide avancé.
