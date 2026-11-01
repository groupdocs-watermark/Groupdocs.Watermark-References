---
title: "Uppdatera vattenmärken"
linkTitle: "Update watermarks"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Sök efter befintliga text- eller bildvattenmärken och uppdatera dem med GroupDocs.Watermark för Python via .NET."
type: docs
url: /sv/python-net/guides/update/
is_root: false
weight: 90
---


Du kan söka i ett dokument efter befintliga vattenmärken och ändra dem på plats — till exempel ersätta texten i ett textvattenmärke eller byta bilden i ett bildvattenmärke.

## Update text watermarks

Sök efter ett vattenmärke efter dess textinnehåll, och tilldela sedan ett nytt värde till varje matchning. Exemplet nedan öppnar ett dokument som redan innehåller ett "CONFIDENTIAL"-vattenmärke och ersätter det med "APPROVED".

{{< tabs "code-example-update">}}
{{< tab "update_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def update_watermark():
    with Watermarker("./watermarked-document.pdf") as watermarker:
        # Hitta de vattenmärken vars text matchar kriterierna
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s).")
        for watermark in possible:
            try:
                watermark.text = "APPROVED"
            except Exception:
                # Vissa hittade objekt stöder inte textredigering — hoppa över dem
                pass
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    update_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.pdf" >}}

`watermarked-document.pdf` är exempelfilen som används i detta exempel. Klicka på [här](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/watermarked-document.pdf) för att ladda ner den.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 444 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/update/update_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

## Update image watermarks

Bildvattenmärken kan hittas med perceptuell hashning ([`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)) och uppdateras genom att tilldela nya byte till `image_data`. Exemplet nedan hittar logotypvattenmärket och ersätter det med ett "APPROVED"-stämpel:

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
                # Vissa hittade objekt stöder inte bildredigering — hoppa över dem
                pass
        watermarker.save("./output.docx")

if __name__ == "__main__":
    update_image_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.docx" >}}

`watermarked-document.docx`, `logo.png` och `stamp.png` är exempel‑filerna som används i detta exempel. Hämta [watermarked-document.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/watermarked-document.docx), [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/logo.png), och [stamp.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/stamp.png).

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 19 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/update/update_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}
