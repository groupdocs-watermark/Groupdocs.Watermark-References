---
title: "Wasserzeichen entfernen"
linkTitle: "Clear watermarks"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Suchen Sie nach vorhandenen Text- oder Bildwasserzeichen und entfernen Sie sie mit GroupDocs.Watermark für Python über .NET."
type: docs
url: /de/python-net/guides/clear/
is_root: false
weight: 100
---


Sie können ein Dokument nach vorhandenen Wasserzeichen durchsuchen und sie entfernen. Das untenstehende Beispiel findet ein Textwasserzeichen "CONFIDENTIAL" und entfernt es, wodurch ein sauberes Dokument entsteht.

## Remove text watermarks

Durchlaufen Sie die Suchergebnisse in umgekehrter Reihenfolge, damit das Entfernen eines Elements die noch zu besuchenden Indizes nicht verschiebt, und rufen Sie `remove()` für jede Übereinstimmung auf.

{{< tabs "code-example-clear">}}
{{< tab "clear_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def clear_watermark():
    with Watermarker("./watermarked-document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        # Entfernen Sie in umgekehrter Reihenfolge, damit die Indizes beim Löschen von Elementen gültig bleiben
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    clear_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.pdf" >}}

`watermarked-document.pdf` ist die in diesem Beispiel verwendete Beispieldatei. Klicken Sie [hier](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/watermarked-document.pdf), um sie herunterzuladen.

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

Bildwasserzeichen können mit perceptuellem Hashing gefunden und auf dieselbe Weise entfernt werden:

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
        # Entfernen Sie in umgekehrter Reihenfolge, damit die Indizes beim Löschen von Elementen gültig bleiben
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.docx")

if __name__ == "__main__":
    clear_image_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.docx" >}}

`watermarked-document.docx` und `logo.png` sind die in diesem Beispiel verwendeten Beispieldateien. Laden Sie [watermarked-document.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/watermarked-document.docx) und [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/logo.png) herunter.

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 13 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/clear/clear_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}
