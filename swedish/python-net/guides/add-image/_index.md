---
title: "Lägg till bildvattenmärken"
linkTitle: "Add image watermarks"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Denna artikel visar hur du lägger till en bildvattenstämpel i ett dokument och sparar resultatet med GroupDocs.Watermark för Python via .NET."
type: docs
url: /sv/python-net/guides/add-image/
is_root: false
weight: 50
---


En av huvudfunktionerna i GroupDocs.Watermark är att lägga till bildvattenmärken i dokument. Du kan lägga till vattenmärken i dokument eller bilder från en lokal sökväg, samt från en ström. För en fullständig lista över stödda format, se [Supported document formats](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/).

## Add an image watermark

För att lägga till en bildvattenstämpel, följ dessa steg:

1. Öppna dokumentet genom att skicka dess sökväg (eller en ström) till klassen [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/).
2. Skapa ett [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) från vattenstämpelns bildfil (eller en ström).
3. Placera vattenstämpeln — till exempel, sätt `horizontal_alignment`, `vertical_alignment` och `opacity`.
4. Anropa `add()` för att applicera vattenstämpeln och `save()` för att skriva resultatet.

{{< tabs "code-example-add-image">}}
{{< tab "add_image_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_image_watermark():
    with Watermarker("./sample.docx") as watermarker:
        # Skapa en bildvattenstämpel från en logofil och centrera den
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

`sample.docx` och `logo.png` är exempel‑filerna som används i detta exempel. Ladda ner [sample.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/sample.docx) och [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/logo.png).

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 127 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-image/add_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}

## What's next

GroupDocs.Watermark erbjuder fler möjligheter för bildvattenmärken — inläsning från strömmar, skalning, mosaik och absolut eller relativ positionering. Se [Adding image watermarks](https://docs.groupdocs.com/watermark/python-net/adding-image-watermarks/) i den avancerade guiden.
