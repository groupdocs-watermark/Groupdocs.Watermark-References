---
title: "WatermarkResult"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt das Ergebnis des Wasserzeichenvorgangs dar, einschließlich Details wie Dokumentgrößen, Verarbeitungszeit und der Anzahl angewendeter Wasserzeichen."
type: docs
weight: 1670
url: /de/net/groupdocs.watermark.internal/watermarkresult/
---
## WatermarkResult class

Stellt das Ergebnis einer Wasserzeichenoperation dar, einschließlich Details wie Dokumentgrößen, Verarbeitungszeit und der Anzahl angewendeter Wasserzeichen.

```csharp
public class WatermarkResult
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [WatermarkResult](watermarkresult#constructor)() | Initialisiert eine neue Instanz der [`WatermarkResult`](../watermarkresult)-Klasse. |
| [WatermarkResult](watermarkresult#constructor_1)(long, TimeSpan, long, int) | Initialisiert eine neue Instanz der [`WatermarkResult`](../watermarkresult)-Klasse mit spezifischen Werten. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [FinalDocumentSize](../../groupdocs.watermark.internal/watermarkresult/finaldocumentsize) { get; } | Liest oder setzt die Größe des endgültig verarbeiteten Dokuments in Bytes. |
| [NumberWatermarksApplied](../../groupdocs.watermark.internal/watermarkresult/numberwatermarksapplied) { get; } | Liest oder setzt die Gesamtzahl der auf das Dokument angewendeten Wasserzeichen. |
| [ProcessingTime](../../groupdocs.watermark.internal/watermarkresult/processingtime) { get; } | Liest oder setzt die Verarbeitungszeit für den Wasserzeichenvorgang. |
| [SourceDocumentSize](../../groupdocs.watermark.internal/watermarkresult/sourcedocumentsize) { get; } | Liest oder setzt die Größe des Quelldokuments in Bytes. |

### Siehe auch

* namespace [GroupDocs.Watermark.Internal](../../groupdocs.watermark.internal)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
