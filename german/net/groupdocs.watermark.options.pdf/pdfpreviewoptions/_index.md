---
title: "PdfPreviewOptions"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Bietet Optionen zum Festlegen von Anforderungen und Stream‑Delegaten für die Vorschauerstellung eines PDF‑Dokuments."
type: docs
weight: 1960
url: /de/net/groupdocs.watermark.options.pdf/pdfpreviewoptions/
---
## PdfPreviewOptions class

Bietet Optionen zum Festlegen von Anforderungen und Stream‑Delegaten für die Vorschauerstellung eines PDF‑Dokuments.

```csharp
public class PdfPreviewOptions : PreviewOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfPreviewOptions](pdfpreviewoptions#constructor)(CreatePageStream) | Initialisiert eine neue Instanz der [`PdfPreviewOptions`](../pdfpreviewoptions)-Klasse, wodurch der Ausgabestream geschlossen wird. |
| [PdfPreviewOptions](pdfpreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Initialisiert eine neue Instanz der [`PdfPreviewOptions`](../pdfpreviewoptions)-Klasse, wodurch der Ausgabestream an den Client zurückgegeben wird, um ihn weiter zu verwenden. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Liest oder legt eine Instanz des Delegaten zur Erstellung des Seitenstreams fest. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Liest oder legt die Höhe der Seitenvorschau fest. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Liest oder legt ein Array von Seitenzahlen fest, für die Vorschauen erzeugt werden sollen. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Liest oder setzt das Vorschaubildformat. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Liest oder setzt eine Instanz des Seitenvorschau-Abschlussdelegaten. |
| [Resolution](../../groupdocs.watermark.options.pdf/pdfpreviewoptions/resolution) { get; set; } | Liest oder setzt die Auflösung für die erzeugten Bilder, in Punkten pro Zoll. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Liest oder setzt die Breite der Seitenvorschau. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.pdf/pdfpreviewoptions/defaultresolution) | Standardauflösung in Punkten pro Zoll. |

### Siehe auch

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
