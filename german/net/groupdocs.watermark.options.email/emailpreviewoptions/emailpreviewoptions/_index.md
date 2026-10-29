---
title: "EmailPreviewOptions"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Initialisiert eine neue Instanz der EmailPreviewOptionsgroupdocs.watermark.options.email/emailpreviewoptions-Klasse, wodurch der Ausgabestream geschlossen wird."
type: docs
weight: 10
url: /de/net/groupdocs.watermark.options.email/emailpreviewoptions/emailpreviewoptions/
---
## EmailPreviewOptions(CreatePageStream) {#constructor}

Initialisiert eine neue Instanz der [`EmailPreviewOptions`](../../emailpreviewoptions)-Klasse, wodurch der Ausgabestream geschlossen wird.

```csharp
public EmailPreviewOptions(CreatePageStream createPageStream)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Erstellt einen Stream für eine bestimmte Seitenvorschau. |

### Siehe auch

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [EmailPreviewOptions](../../emailpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Email](../../../groupdocs.watermark.options.email)
* assembly [GroupDocs.Watermark](../../../)

---

## EmailPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initialisiert eine neue Instanz der [`EmailPreviewOptions`](../../emailpreviewoptions)-Klasse, wodurch der Ausgabestream an den Client zurückgegeben wird, um ihn weiter zu verwenden.

```csharp
public EmailPreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Erstellt einen Stream für eine bestimmte Seitenvorschau. |
| releasePageStream | ReleasePageStream | Benachrichtigt, dass die Generierung der Seitenvorschau abgeschlossen ist, und ruft den Ausgabestream ab. |

### Siehe auch

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [EmailPreviewOptions](../../emailpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Email](../../../groupdocs.watermark.options.email)
* assembly [GroupDocs.Watermark](../../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
