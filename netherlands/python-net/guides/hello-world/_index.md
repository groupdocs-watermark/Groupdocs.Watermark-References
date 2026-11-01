---
title: "Hallo, Wereld!"
linkTitle: "Hello, World!"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Start snel met GroupDocs.Watermark voor Python via .NET door een eenvoudig voorbeeld te maken en uit te voeren."
type: docs
url: /nl/python-net/guides/hello-world/
is_root: false
weight: 20
---


## Introduction
Een \"Hallo, Wereld!\"‑voorbeeld is vaak de eerste stap bij het verkennen van GroupDocs.Watermark voor Python via .NET. Het dient als een eenvoudige test om te bevestigen dat je ontwikkelomgeving correct is ingesteld en dat de bibliotheek naar verwachting functioneert.

## Overview
GroupDocs.Watermark voor Python via .NET laat je watermerken toevoegen, zoeken en verwijderen in verschillende documentformaten. Een breed scala aan [supported formats](https://docs.groupdocs.com/watermark/python-net/getting-started/supported-document-formats/) maakt het veelzijdig voor verschillende gebruikssituaties.

## How to add a watermark
De volgende stappen laten zien hoe u een tekstwatermerk aan een document toevoegt met GroupDocs.Watermark voor Python via .NET:

1. Importeer de `groupdocs.watermark`-klassen die u nodig heeft.
2. Open een [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) met het pad naar het voorbeelddocument.
3. Maak een [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) met de gewenste tekst en lettertype, en styleer deze.
4. Pas het watermerk toe met `add()`.
5. Sla het resultaat op.

## Complete example
Het onderstaande voorbeeld voegt een semi-transparant, diagonaal "Hello, Watermark!" tekstwatermerk toe en slaat het resultaat op:

{{< tabs \"code-example-hello-world\" >}}
{{< tab \"hello_world.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

def hello_world():
    # Open het document, voeg een enkel tekstwatermerk toe, en sla het resultaat op
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

`sample.pdf` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/watermark/python-net/_sample_files/getting-started/hello-world/sample.pdf) om het te downloaden.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 315 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/getting-started/hello-world/hello_world/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Het watermerk wordt terug opgeslagen in hetzelfde PDF-formaat als `output.pdf`. Om een ander document te voorzien van een stempel, wijzig het invoerpad en de uitvoerextensie — GroupDocs.Watermark slaat op in het formaat van het invoerdocument.

## Additional resources
Deze demo verwijst naar de GroupDocs.Watermark voor Python via .NET [codevoorbeelden](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET/).
