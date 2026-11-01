---
title: "Watermerken verwijderen"
linkTitle: "Clear watermarks"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Zoek naar en verwijder bestaande tekst- of afbeeldingwatermerken met GroupDocs.Watermark voor Python via .NET."
type: docs
url: /nl/python-net/guides/clear/
is_root: false
weight: 100
---


U kunt een document doorzoeken op bestaande watermerken en deze verwijderen. Het onderstaande voorbeeld vindt een tekstwatermerk "CONFIDENTIAL" en verwijdert het, waardoor een schoon document ontstaat.

## Remove text watermarks

Itereer de zoekresultaten in omgekeerde volgorde zodat het verwijderen van een item de nog te bezoeken indexen niet verschuift, en roep `remove()` aan voor elke overeenkomst.

{{< tabs "code-example-clear">}}
{{< tab "clear_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def clear_watermark():
    with Watermarker("./watermarked-document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        # Verwijder in omgekeerde volgorde zodat indexen geldig blijven terwijl items worden verwijderd
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    clear_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.pdf" >}}

`watermarked-document.pdf` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/watermarked-document.pdf) om het te downloaden.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 360 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/clear/clear_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

**Use case:** Remove outdated labels such as "Draft" or "Internal Use Only" before sharing a document externally.

## Remove image watermarks

Afbeeldingswatermerken kunnen worden gevonden met perceptueel hashen en op dezelfde manier worden verwijderd:

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
        # Verwijder in omgekeerde volgorde zodat indexen geldig blijven terwijl items worden verwijderd
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.docx")

if __name__ == "__main__":
    clear_image_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.docx" >}}

`watermarked-document.docx` en `logo.png` zijn de voorbeeldbestanden die in dit voorbeeld worden gebruikt. Download [watermarked-document.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/watermarked-document.docx) en [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/logo.png).

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 13 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/clear/clear_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}
