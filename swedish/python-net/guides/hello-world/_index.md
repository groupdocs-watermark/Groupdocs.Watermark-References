---
title: "Hej, världen!"
linkTitle: "Hello, World!"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Kom snabbt igång med GroupDocs.Watermark för Python via .NET genom att skapa och köra ett enkelt exempel."
type: docs
url: /sv/python-net/guides/hello-world/
is_root: false
weight: 20
---


## Introduction
Ett \"Hello, World!\"-exempel är ofta det första steget när man utforskar GroupDocs.Watermark för Python via .NET. Det fungerar som ett enkelt test för att bekräfta att din utvecklingsmiljö är korrekt konfigurerad och att biblioteket fungerar som förväntat.

## Overview
GroupDocs.Watermark för Python via .NET låter dig lägga till, söka och ta bort vattenmärken i olika dokumentformat. Ett brett urval av [stödda format](https://docs.groupdocs.com/watermark/python-net/getting-started/supported-document-formats/) gör det mångsidigt för olika användningsfall.

## How to add a watermark
Följande steg visar hur du lägger till ett textvattenmärke i ett dokument med hjälp av GroupDocs.Watermark för Python via .NET:

1. Importera de `groupdocs.watermark`-klasser du behöver.
2. Öppna en [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) med sökvägen till exempeldokumentet.
3. Skapa ett [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) med önskad text och teckensnitt, och formatera det.
4. Applicera vattenmärket med `add()`.
5. Spara resultatet.

## Complete example
Exemplet nedan lägger till ett halvtransparent, diagonalt \"Hello, Watermark!\"-textvattenmärke och sparar resultatet:

{{< tabs \"code-example-hello-world\" >}}
{{< tab \"hello_world.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

def hello_world():
    # Öppna dokumentet, lägg till ett enda textvattenmärke och spara resultatet
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
{{< tab "sample.pdf" >}}

`sample.pdf` är exempel‑filen som används i detta exempel. Klicka på [här](https://docs.groupdocs.com/watermark/python-net/_sample_files/getting-started/hello-world/sample.pdf) för att ladda ner den.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 315 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/getting-started/hello-world/hello_world/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Vattenmärket sparas tillbaka i samma PDF-format som `output.pdf`. För att stämpla ett annat dokument, ändra inmatningssökvägen och utdata‑filändelsen — GroupDocs.Watermark sparar i det inmatade dokumentets format.

## Additional resources
Denna demo refererar till GroupDocs.Watermark för Python via .NET [kodexempel](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET/).
