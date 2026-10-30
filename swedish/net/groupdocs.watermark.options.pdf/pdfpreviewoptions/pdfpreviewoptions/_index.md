---
title: "PdfPreviewOptions"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Initierar en ny instans av klassen PdfPreviewOptionsgroupdocs.watermark.options.pdf/pdfpreviewoptions som gör att utdataströmmen stängs."
type: docs
weight: 10
url: /sv/net/groupdocs.watermark.options.pdf/pdfpreviewoptions/pdfpreviewoptions/
---
## PdfPreviewOptions(CreatePageStream) {#constructor}

Initierar en ny instans av klassen [`PdfPreviewOptions`](../../pdfpreviewoptions) som gör att utdataströmmen stängs.

```csharp
public PdfPreviewOptions(CreatePageStream createPageStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Skapar ett flöde för en specifik sidoförhandsgranskning. |

### Se även

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [PdfPreviewOptions](../../pdfpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../../)

---

## PdfPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initierar en ny instans av klassen [`PdfPreviewOptions`](../../pdfpreviewoptions) som gör att utdataströmmen returneras till klienten för vidare användning.

```csharp
public PdfPreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Skapar ett flöde för en specifik sidoförhandsgranskning. |
| releasePageStream | ReleasePageStream | Meddelar att sidoförhandsgranskningens generering är klar och hämtar utdataflödet. |

### Se även

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [PdfPreviewOptions](../../pdfpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
