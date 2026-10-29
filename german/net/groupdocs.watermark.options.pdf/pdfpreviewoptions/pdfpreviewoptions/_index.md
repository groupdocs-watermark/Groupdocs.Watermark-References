---
title: "PdfPreviewOptions"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Initialisiert eine neue Instanz der PdfPreviewOptionsgroupdocs.watermark.options.pdf/pdfpreviewoptions-Klasse, die den Ausgabestream schließt."
type: docs
weight: 10
url: /de/net/groupdocs.watermark.options.pdf/pdfpreviewoptions/pdfpreviewoptions/
---
## PdfPreviewOptions(CreatePageStream) {#constructor}

Initialisiert eine neue Instanz der [`PdfPreviewOptions`](../../pdfpreviewoptions)-Klasse, die den Ausgabestream schließt.

```csharp
public PdfPreviewOptions(CreatePageStream createPageStream)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Erstellt einen Stream für eine bestimmte Seitenvorschau. |

### Siehe auch

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [PdfPreviewOptions](../../pdfpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../../)

---

## PdfPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initialisiert eine neue Instanz der [`PdfPreviewOptions`](../../pdfpreviewoptions)-Klasse, die den Ausgabestream an den Client zurückgibt, um ihn weiter zu verwenden.

```csharp
public PdfPreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Erstellt einen Stream für eine bestimmte Seitenvorschau. |
| releasePageStream | ReleasePageStream | Benachrichtigt, dass die Generierung der Seitenvorschau abgeschlossen ist, und ruft den Ausgabestream ab. |

### Siehe auch

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [PdfPreviewOptions](../../pdfpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
