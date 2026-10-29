---
title: "WordProcessingPreviewOptions"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Initialisiert eine neue Instanz der WordProcessingPreviewOptionsgroupdocs.watermark.options.wordprocessing/wordprocessingpreviewoptions Klasse, wodurch der Ausgabestream geschlossen wird."
type: docs
weight: 10
url: /de/net/groupdocs.watermark.options.wordprocessing/wordprocessingpreviewoptions/wordprocessingpreviewoptions/
---
## WordProcessingPreviewOptions(CreatePageStream) {#constructor}

Initialisiert eine neue Instanz der [`WordProcessingPreviewOptions`](../../wordprocessingpreviewoptions) Klasse, wodurch der Ausgabestream geschlossen wird.

```csharp
public WordProcessingPreviewOptions(CreatePageStream createPageStream)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Erstellt einen Stream für eine bestimmte Seitenvorschau. |

### Siehe auch

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [WordProcessingPreviewOptions](../../wordprocessingpreviewoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../../)

---

## WordProcessingPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initialisiert eine neue Instanz der [`WordProcessingPreviewOptions`](../../wordprocessingpreviewoptions) Klasse, wodurch der Ausgabestream an den Client zurückgegeben wird für weitere Verwendung.

```csharp
public WordProcessingPreviewOptions(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Erstellt einen Stream für eine bestimmte Seitenvorschau. |
| releasePageStream | ReleasePageStream | Benachrichtigt, dass die Generierung der Seitenvorschau abgeschlossen ist, und ruft den Ausgabestream ab. |

### Siehe auch

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [WordProcessingPreviewOptions](../../wordprocessingpreviewoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
