---
title: "Lägg till textvattenmärken"
linkTitle: "Add text watermarks"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Den här artikeln visar hur man lägger till en textvattenstämpel i ett dokument och sparar resultatet med GroupDocs.Watermark för Python via .NET."
type: docs
url: /sv/python-net/guides/add-text/
is_root: false
weight: 40
---


En av huvudfunktionerna i GroupDocs.Watermark är att lägga till textvattenmärken i dokument. Du kan lägga till vattenmärken i dokument eller bilder från en lokal sökväg, samt från en ström. För en fullständig lista över stödjade format, se [Supported document formats](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/).

## Add a text watermark

För att lägga till en textvattenstämpel, följ dessa steg:

1. Öppna dokumentet genom att skicka dess sökväg (eller en ström) till klassen [Watermarker](https://reference.groupdocs.com/watermark/python-net/) och använd ett `with`‑block så att dokumentet frigörs automatiskt.
2. Skapa ett [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) med önskad text och en [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/).
3. Formatera vattenstämpeln — till exempel, sätt `foreground_color` och justering.
4. Anropa `add()` för att applicera vattenstämpeln och `save()` för att skriva resultatet.

{{< tabs \"code-example-add-text\">}}
{{< tab \"add_text_watermark.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_text_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        # Bygg textvattenstämpeln och formatera den
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
{{< tab "sample.pdf" >}}

`sample.pdf` är exempelfilen som används i detta exempel. Klicka på [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-text/sample.pdf) för att ladda ner den.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 313 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-text/add_text_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Kör programmet. Ett nytt vattenstämplat dokument visas på den angivna sökvägen.

## What's next

GroupDocs.Watermark erbjuder många fler funktioner för textvattenmärken — bakgrunds- och förgrundsfärger, anpassade typsnitt, opacitet, rotation, mosaik, samt absolut eller relativ positionering. Se [Adding text watermarks](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/) i den avancerade guiden.
