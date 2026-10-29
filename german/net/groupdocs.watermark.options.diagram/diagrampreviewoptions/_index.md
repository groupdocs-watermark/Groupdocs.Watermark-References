---
title: "DiagramPreviewOptions"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Bietet Optionen zum Festlegen von Anforderungen und Stream‑Delegaten für die Vorschauerstellung eines Diagramm‑Dokuments."
type: docs
weight: 1730
url: /de/net/groupdocs.watermark.options.diagram/diagrampreviewoptions/
---
## DiagramPreviewOptions class

Bietet Optionen zum Festlegen von Anforderungen und Stream‑Delegaten für die Vorschauerstellung eines Diagramm‑Dokuments.

```csharp
public class DiagramPreviewOptions : PreviewOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [DiagramPreviewOptions](diagrampreviewoptions#constructor)(CreatePageStream) | Initialisiert eine neue Instanz der Klasse [`DiagramPreviewOptions`](../diagrampreviewoptions), wodurch der Ausgabestream geschlossen wird. |
| [DiagramPreviewOptions](diagrampreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Initialisiert eine neue Instanz der Klasse [`DiagramPreviewOptions`](../diagrampreviewoptions), wodurch der Ausgabestream dem Client zur weiteren Verwendung zurückgegeben wird. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Liest oder legt eine Instanz des Delegaten zur Erstellung des Seitenstreams fest. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Liest oder legt die Höhe der Seitenvorschau fest. |
| [HighQualityRendering](../../groupdocs.watermark.options.diagram/diagrampreviewoptions/highqualityrendering) { get; set; } | Liest oder setzt das Flag für die hochqualitative Darstellung. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Liest oder legt ein Array von Seitenzahlen fest, für die Vorschauen erzeugt werden sollen. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Liest oder setzt das Vorschaubildformat. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Liest oder setzt eine Instanz des Seitenvorschau-Abschlussdelegaten. |
| [Resolution](../../groupdocs.watermark.options.diagram/diagrampreviewoptions/resolution) { get; set; } | Liest oder setzt die Auflösung für die erzeugten Bilder, in Punkten pro Zoll. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Liest oder setzt die Breite der Seitenvorschau. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.diagram/diagrampreviewoptions/defaultresolution) | Standardauflösung in Punkten pro Zoll. |

### Siehe auch

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
