---
title: "Bildwasserzeichen hinzufügen"
linkTitle: "Add image watermarks"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Dieser Artikel zeigt, wie man ein Bildwasserzeichen zu einem Dokument hinzufügt und das Ergebnis mit GroupDocs.Watermark für Python über .NET speichert."
type: docs
url: /de/python-net/guides/add-image/
is_root: false
weight: 50
---


Eine der Hauptfunktionen von GroupDocs.Watermark ist das Hinzufügen von Bildwasserzeichen zu Dokumenten. Sie können Wasserzeichen zu Dokumenten oder Bildern von einem lokalen Pfad sowie von einem Stream hinzufügen. Für eine vollständige Liste der unterstützten Formate prüfen Sie [Supported document formats](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/).

## Add an image watermark

Um ein Bildwasserzeichen hinzuzufügen, folgen Sie diesen Schritten:

1. Öffnen Sie das Dokument, indem Sie seinen Pfad (oder einen Stream) an die Klasse [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) übergeben.
2. Erstellen Sie ein [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) aus der Wasserzeichen‑Bilddatei (oder einem Stream).
3. Positionieren Sie das Wasserzeichen – zum Beispiel setzen Sie `horizontal_alignment`, `vertical_alignment` und `opacity`.
4. Rufen Sie `add()` auf, um das Wasserzeichen anzuwenden, und `save()`, um das Ergebnis zu schreiben.

{{< tabs "code-example-add-image">}}
{{< tab "add_image_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_image_watermark():
    with Watermarker("./sample.docx") as watermarker:
        # Erstellen Sie ein Bildwasserzeichen aus einer Logodatei und zentrieren Sie es
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

`sample.docx` und `logo.png` sind die Beispieldateien, die in diesem Beispiel verwendet werden. Laden Sie [sample.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/sample.docx) und [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/logo.png) herunter.

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 127 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-image/add_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}

## What's next

GroupDocs.Watermark bietet weitere Möglichkeiten für Bildwasserzeichen – Laden aus Streams, Skalierung, Kachelung und absolute oder relative Positionierung. Siehe [Adding image watermarks](https://docs.groupdocs.com/watermark/python-net/adding-image-watermarks/) im erweiterten Leitfaden.
