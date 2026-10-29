---
title: "PreviewOptions"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Bietet Optionen zum Festlegen von Anforderungen und Stream-Delegaten für die Vorschauerstellung."
type: docs
weight: 2140
url: /de/net/groupdocs.watermark.options/previewoptions/
---
## PreviewOptions class

Bietet Optionen zum Festlegen von Anforderungen und Stream-Delegaten für die Vorschauerstellung.

```csharp
public class PreviewOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PreviewOptions](previewoptions#constructor)(CreatePageStream) | Initialisiert eine neue Instanz der Klasse [`PreviewOptions`](../previewoptions), wodurch der Ausgabestream geschlossen wird. |
| [PreviewOptions](previewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Initialisiert eine neue Instanz der Klasse [`PreviewOptions`](../previewoptions), wodurch der Ausgabestream dem Client für weitere Verwendung zurückgegeben wird. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Liest oder legt eine Instanz des Delegaten zur Erstellung des Seitenstreams fest. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Liest oder legt die Höhe der Seitenvorschau fest. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Liest oder legt ein Array von Seitenzahlen fest, für die Vorschauen erzeugt werden sollen. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Liest oder setzt das Vorschaubildformat. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Liest oder setzt eine Instanz des Seitenvorschau-Abschlussdelegaten. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Liest oder setzt die Breite der Seitenvorschau. |

### Siehe auch

* namespace [GroupDocs.Watermark.Options](../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
