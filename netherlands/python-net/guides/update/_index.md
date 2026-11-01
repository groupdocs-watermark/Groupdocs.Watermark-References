---
title: "Watermerken bijwerken"
linkTitle: "Update watermarks"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Zoek naar bestaande tekst- of afbeeldingwatermerken en werk ze bij met GroupDocs.Watermark voor Python via .NET."
type: docs
url: /nl/python-net/guides/update/
is_root: false
weight: 90
---


U kunt een document doorzoeken op bestaande watermerken en ze ter plaatse aanpassen — bijvoorbeeld de tekst van een tekstwatermerk vervangen of de afbeelding van een afbeeldingwatermerk wisselen.

## Update text watermarks

Zoek een watermerk op basis van de tekstinhoud, en wijs vervolgens een nieuwe waarde toe aan elke overeenkomst. Het onderstaande voorbeeld opent een document dat al een "CONFIDENTIAL" watermerk bevat en vervangt dit door "APPROVED".

{{< tabs "code-example-update">}}
{{< tab "update_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def update_watermark():
    with Watermarker("./watermarked-document.pdf") as watermarker:
        # Zoek de watermerken waarvan de tekst aan de criteria voldoet
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s).")
        for watermark in possible:
            try:
                watermark.text = "APPROVED"
            except Exception:
                # Sommige gevonden entiteiten ondersteunen geen tekstbewerking — sla ze over
                pass
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    update_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.pdf" >}}

`watermarked-document.pdf` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/watermarked-document.pdf) om het te downloaden.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 444 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/update/update_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

## Update image watermarks

Afbeeldingswatermerken kunnen worden gevonden met perceptueel hashen ([`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)) en bijgewerkt door nieuwe bytes toe te wijzen aan `image_data`. Het onderstaande voorbeeld vindt het logo-watermerk en vervangt het door een "APPROVED" stempel:

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
                # Sommige gevonden entiteiten ondersteunen geen beeldbewerking — sla ze over
                pass
        watermarker.save("./output.docx")

if __name__ == "__main__":
    update_image_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.docx" >}}

`watermarked-document.docx`, `logo.png`, en `stamp.png` zijn de voorbeeldbestanden die in dit voorbeeld worden gebruikt. Download [watermarked-document.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/watermarked-document.docx), [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/logo.png), en [stamp.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/stamp.png).

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 19 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/update/update_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}
