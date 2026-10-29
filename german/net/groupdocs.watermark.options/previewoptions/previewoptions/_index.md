---
title: "PreviewOptions"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Initialisiert eine neue Instanz der Klasse PreviewOptionsgroupdocs.watermark.options/previewoptions, die den Ausgabestream schließt."
type: docs
weight: 10
url: /de/net/groupdocs.watermark.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream) {#constructor}

Initialisiert eine neue Instanz der Klasse [`PreviewOptions`](../../previewoptions), die den Ausgabestream schließt.

```csharp
public PreviewOptions(CreatePageStream createPageStream)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Erstellt einen Stream für eine bestimmte Seitenvorschau. |

### Siehe auch

* delegate [CreatePageStream](../../createpagestream)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Watermark.Options](../../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initialisiert eine neue Instanz der Klasse [`PreviewOptions`](../../previewoptions), die den Ausgabestream an den Client zurückgibt, um ihn weiter zu verwenden.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Erstellt einen Stream für eine bestimmte Seitenvorschau. |
| releasePageStream | ReleasePageStream | Benachrichtigt, dass die Generierung der Seitenvorschau abgeschlossen ist, und ruft den Ausgabestream ab. |

### Siehe auch

* delegate [CreatePageStream](../../createpagestream)
* delegate [ReleasePageStream](../../releasepagestream)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Watermark.Options](../../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
