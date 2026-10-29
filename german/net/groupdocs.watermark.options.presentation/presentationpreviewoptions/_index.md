---
title: "PresentationPreviewOptions"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Bietet Optionen, um Anforderungen festzulegen und Stream-Delegaten für die Vorschauerstellung eines Präsentationsdokuments zu definieren."
type: docs
weight: 2030
url: /de/net/groupdocs.watermark.options.presentation/presentationpreviewoptions/
---
## PresentationPreviewOptions class

Bietet Optionen, um Anforderungen festzulegen und Stream-Delegaten für die Vorschauerstellung eines Präsentationsdokuments zu definieren.

```csharp
public class PresentationPreviewOptions : PreviewOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PresentationPreviewOptions](presentationpreviewoptions#constructor)(CreatePageStream) | Initialisiert eine neue Instanz der [`PresentationPreviewOptions`](../presentationpreviewoptions) Klasse, die den Ausgabestream schließt. |
| [PresentationPreviewOptions](presentationpreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Initialisiert eine neue Instanz der [`PresentationPreviewOptions`](../presentationpreviewoptions) Klasse, die den Ausgabestream an den Client zurückgibt, damit er weiter verwendet werden kann. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Liest oder legt eine Instanz des Delegaten zur Erstellung des Seitenstreams fest. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Liest oder legt die Höhe der Seitenvorschau fest. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Liest oder legt ein Array von Seitenzahlen fest, für die Vorschauen erzeugt werden sollen. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Liest oder setzt das Vorschaubildformat. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Liest oder setzt eine Instanz des Seitenvorschau-Abschlussdelegaten. |
| [Resolution](../../groupdocs.watermark.options.presentation/presentationpreviewoptions/resolution) { get; set; } | Liest oder setzt die Auflösung für die erzeugten Bilder, in Punkten pro Zoll. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Liest oder setzt die Breite der Seitenvorschau. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.presentation/presentationpreviewoptions/defaultresolution) | Standardauflösung in Punkten pro Zoll. |

### Siehe auch

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
