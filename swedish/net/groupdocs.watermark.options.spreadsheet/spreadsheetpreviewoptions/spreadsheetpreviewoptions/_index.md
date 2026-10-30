---
title: "SpreadsheetPreviewOptions"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Initierar en ny instans av klassen SpreadsheetPreviewOptionsgroupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions som gör att utdataströmmen stängs."
type: docs
weight: 10
url: /sv/net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/spreadsheetpreviewoptions/
---
## SpreadsheetPreviewOptions(CreatePageStream) {#constructor}

Initierar en ny instans av klassen [`SpreadsheetPreviewOptions`](../../spreadsheetpreviewoptions) som gör att utdataströmmen stängs.

```csharp
public SpreadsheetPreviewOptions(CreatePageStream createPageStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Skapar ett flöde för en specifik sidoförhandsgranskning. |

### Se även

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [SpreadsheetPreviewOptions](../../spreadsheetpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../../)

---

## SpreadsheetPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initierar en ny instans av [`SpreadsheetPreviewOptions`](../../spreadsheetpreviewoptions) som gör att utdataströmmen returneras till klienten för vidare användning.

```csharp
public SpreadsheetPreviewOptions(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Skapar ett flöde för en specifik sidoförhandsgranskning. |
| releasePageStream | ReleasePageStream | Meddelar att sidoförhandsgranskningens generering är klar och hämtar utdataflödet. |

### Se även

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [SpreadsheetPreviewOptions](../../spreadsheetpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
