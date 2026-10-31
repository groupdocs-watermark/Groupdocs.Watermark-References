---
title: "Wasserzeichen aktualisieren"
linkTitle: "Update watermarks"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Suchen Sie nach vorhandenen Text- oder Bildwasserzeichen und aktualisieren Sie sie mit GroupDocs.Watermark für Python über .NET."
type: docs
url: /de/python-net/guides/update/
is_root: false
weight: 90
---


Sie können ein Dokument nach vorhandenen Wasserzeichen durchsuchen und sie direkt ändern – zum Beispiel den Text eines Textwasserzeichens ersetzen oder das Bild eines Bildwasserzeichens austauschen.

## Update text watermarks

Suchen Sie ein Wasserzeichen nach seinem Textinhalt und weisen Sie jeder Übereinstimmung einen neuen Wert zu. Das untenstehende Beispiel öffnet ein Dokument, das bereits ein "CONFIDENTIAL"-Wasserzeichen enthält, und ersetzt es durch "APPROVED".

{{< tabs "code-example-update">}}
{{< tab "update_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def update_watermark():
    with Watermarker("./watermarked-document.pdf") as watermarker:
        # Finden Sie die Wasserzeichen, deren Text den Kriterien entspricht
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s).")
        for watermark in possible:
            try:
                watermark.text = "APPROVED"
            except Exception:
                # Einige gefundene Entitäten unterstützen keine Textbearbeitung – überspringen Sie sie
                pass
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    update_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.pdf" >}}

`watermarked-document.pdf` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/watermarked-document.pdf) zum Herunterladen.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 444 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/update/update_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

## Update image watermarks

Bildwasserzeichen können mit perceptuellem Hashing gefunden werden ([`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)) und aktualisiert werden, indem neue Bytes an `image_data` zugewiesen werden. Das nachstehende Beispiel findet das Logo‑Wasserzeichen und ersetzt es durch einen "APPROVED"-Stempel:

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
                # Einige gefundene Entitäten unterstützen keine Bildbearbeitung — überspringen Sie sie.
                pass
        watermarker.save("./output.docx")

if __name__ == "__main__":
    update_image_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.docx" >}}

`watermarked-document.docx`, `logo.png` und `stamp.png` sind die Beispieldateien, die in diesem Beispiel verwendet werden. Laden Sie [watermarked-document.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/watermarked-document.docx), [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/logo.png) und [stamp.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/stamp.png) herunter.

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 19 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/update/update_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}
