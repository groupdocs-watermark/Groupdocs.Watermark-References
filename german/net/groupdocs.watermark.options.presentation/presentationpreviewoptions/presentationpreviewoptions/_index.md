---
title: "PresentationPreviewOptions"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Initialisiert eine neue Instanz der PresentationPreviewOptionsgroupdocs.watermark.options.presentation/presentationpreviewoptions Klasse, wobei der Ausgabestream geschlossen wird."
type: docs
weight: 10
url: /de/net/groupdocs.watermark.options.presentation/presentationpreviewoptions/presentationpreviewoptions/
---
## PresentationPreviewOptions(CreatePageStream) {#constructor}

Initialisiert eine neue Instanz der [`PresentationPreviewOptions`](../../presentationpreviewoptions) Klasse, wobei der Ausgabestream geschlossen wird.

```csharp
public PresentationPreviewOptions(CreatePageStream createPageStream)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Erstellt einen Stream für eine bestimmte Seitenvorschau. |

### Siehe auch

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [PresentationPreviewOptions](../../presentationpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../../)

---

## PresentationPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initialisiert eine neue Instanz von [`PresentationPreviewOptions`](../../presentationpreviewoptions) Klasse, wobei der Ausgabestream dem Client zur weiteren Verwendung zurückgegeben wird.

```csharp
public PresentationPreviewOptions(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Erstellt einen Stream für eine bestimmte Seitenvorschau. |
| releasePageStream | ReleasePageStream | Benachrichtigt, dass die Generierung der Seitenvorschau abgeschlossen ist, und ruft den Ausgabestream ab. |

### Siehe auch

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [PresentationPreviewOptions](../../presentationpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
