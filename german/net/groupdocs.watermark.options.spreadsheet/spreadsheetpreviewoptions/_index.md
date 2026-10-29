---
title: "SpreadsheetPreviewOptions"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt Optionen bereit, um Anforderungen und Stream-Delegaten für die Vorschauerstellung eines Spreadsheet-Dokuments festzulegen."
type: docs
weight: 2220
url: /de/net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/
---
## SpreadsheetPreviewOptions class

Stellt Optionen bereit, um Anforderungen und Stream-Delegaten für die Vorschauerstellung eines Spreadsheet-Dokuments festzulegen.

```csharp
public class SpreadsheetPreviewOptions : PreviewOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SpreadsheetPreviewOptions](spreadsheetpreviewoptions#constructor)(CreatePageStream) | Initialisiert eine neue Instanz der [`SpreadsheetPreviewOptions`](../spreadsheetpreviewoptions)-Klasse, wodurch der Ausgabestream geschlossen wird. |
| [SpreadsheetPreviewOptions](spreadsheetpreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Initialisiert eine neue Instanz der [`SpreadsheetPreviewOptions`](../spreadsheetpreviewoptions)-Klasse, wodurch der Ausgabestream dem Client für weitere Verwendung zurückgegeben wird. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Liest oder legt eine Instanz des Delegaten zur Erstellung des Seitenstreams fest. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Liest oder legt die Höhe der Seitenvorschau fest. |
| [OnlyDataArea](../../groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/onlydataarea) { get; set; } | Liest oder setzt das Flag für die Darstellung nur des Datenbereichs ohne Kopfzeilen, Fußzeilen und Ränder. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Liest oder legt ein Array von Seitenzahlen fest, für die Vorschauen erzeugt werden sollen. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Liest oder setzt das Vorschaubildformat. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Liest oder setzt eine Instanz des Seitenvorschau-Abschlussdelegaten. |
| [Resolution](../../groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/resolution) { get; set; } | Liest oder setzt die Auflösung für die erzeugten Bilder, in Punkten pro Zoll. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Liest oder setzt die Breite der Seitenvorschau. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/defaultresolution) | Standardauflösung in Punkten pro Zoll. |

### Siehe auch

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
