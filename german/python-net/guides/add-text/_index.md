---
title: "Text‑Wasserzeichen hinzufügen"
linkTitle: "Add text watermarks"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Dieser Artikel zeigt, wie man einem Dokument ein Text‑Wasserzeichen hinzufügt und das Ergebnis mit GroupDocs.Watermark für Python über .NET speichert."
type: docs
url: /de/python-net/guides/add-text/
is_root: false
weight: 40
---


Eine der Hauptfunktionen von GroupDocs.Watermark ist das Hinzufügen von Text‑Wasserzeichen zu Dokumenten. Sie können Wasserzeichen zu Dokumenten oder Bildern von einem lokalen Pfad sowie aus einem Stream hinzufügen. Für eine vollständige Liste der unterstützten Formate siehe [Supported document formats](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/).

## Add a text watermark

Um ein Text‑Wasserzeichen hinzuzufügen, folgen Sie diesen Schritten:

1. Öffnen Sie das Dokument, indem Sie dessen Pfad (oder einen Stream) an die [Watermarker](https://reference.groupdocs.com/watermark/python-net/)‑Klasse übergeben und dabei einen `with`‑Block verwenden, sodass das Dokument automatisch freigegeben wird.
2. Erstellen Sie ein [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) mit dem gewünschten Text und einer [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/).
3. Gestalten Sie das Wasserzeichen – zum Beispiel, setzen Sie `foreground_color` und die Ausrichtung.
4. Rufen Sie `add()` auf, um das Wasserzeichen anzuwenden, und `save()`, um das Ergebnis zu schreiben.

{{< tabs "code-example-add-text">}}
{{< tab "add_text_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_text_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        # Erstellen Sie das Text‑Wasserzeichen und formatieren Sie es
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

`sample.pdf` ist die in diesem Beispiel verwendete Beispieldatei. Klicken Sie [hier](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-text/sample.pdf) zum Herunterladen.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 313 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-text/add_text_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Führen Sie das Programm aus. Ein neues, mit Wasserzeichen versehenes Dokument erscheint am angegebenen Pfad.

## What's next

GroupDocs.Watermark bietet viele weitere Funktionen für Textwasserzeichen — Hintergrund‑ und Vordergrundfarben, benutzerdefinierte Schriftarten, Transparenz, Drehung, Kachelung sowie absolute oder relative Positionierung. Siehe [Adding text watermarks](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/) im erweiterten Leitfaden.
