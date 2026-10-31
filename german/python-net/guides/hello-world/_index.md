---
title: "Hallo, Welt!"
linkTitle: "Hello, World!"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Starten Sie schnell mit GroupDocs.Watermark für Python via .NET, indem Sie ein einfaches Beispiel erstellen und ausführen."
type: docs
url: /de/python-net/guides/hello-world/
is_root: false
weight: 20
---


## Introduction
Ein "Hello, World!"‑Beispiel ist oft der erste Schritt beim Erkunden von GroupDocs.Watermark für Python via .NET. Es dient als einfacher Test, um zu bestätigen, dass Ihre Entwicklungsumgebung korrekt eingerichtet ist und die Bibliothek wie erwartet funktioniert.

## Overview
GroupDocs.Watermark für Python via .NET ermöglicht das Hinzufügen, Suchen und Entfernen von Wasserzeichen in verschiedenen Dokumentformaten. Eine große Auswahl an [supported formats](https://docs.groupdocs.com/watermark/python-net/getting-started/supported-document-formats/) macht es für unterschiedliche Anwendungsfälle vielseitig.

## How to add a watermark
Die folgenden Schritte zeigen, wie man mit GroupDocs.Watermark für Python via .NET ein Textwasserzeichen zu einem Dokument hinzufügt:

1. Importieren Sie die benötigten `groupdocs.watermark`‑Klassen.
2. Öffnen Sie einen [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) mit dem Pfad zum Beispieldokument.
3. Erstellen Sie ein [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) mit dem gewünschten Text und der gewünschten Schriftart und formatieren Sie es.
4. Wenden Sie das Wasserzeichen mit `add()` an.
5. Speichern Sie das Ergebnis.

## Complete example
Das nachstehende Beispiel fügt ein halbtransparentes, diagonales "Hello, Watermark!"‑Textwasserzeichen hinzu und speichert das Ergebnis:

{{< tabs \"code-example-hello-world\" >}}
{{< tab \"hello_world.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

def hello_world():
    # Öffnen Sie das Dokument, fügen Sie ein einzelnes Textwasserzeichen hinzu und speichern Sie das Ergebnis
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

`sample.pdf` ist die in diesem Beispiel verwendete Beispieldatei. Klicken Sie [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/getting-started/hello-world/sample.pdf), um sie herunterzuladen.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 315 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/getting-started/hello-world/hello_world/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Das Wasserzeichen wird wieder im selben PDF‑Format wie `output.pdf` gespeichert. Um ein anderes Dokument zu versehen, ändern Sie den Eingabepfad und die Ausgabenerweiterung — GroupDocs.Watermark speichert im Format des Eingabedokuments.

## Additional resources
Dieses Demo verweist auf die GroupDocs.Watermark für Python via .NET [code samples](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET/).
