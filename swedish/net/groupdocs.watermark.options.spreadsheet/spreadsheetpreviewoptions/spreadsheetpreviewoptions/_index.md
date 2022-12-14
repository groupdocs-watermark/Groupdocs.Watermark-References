---
title: SpreadsheetPreviewOptions
second_title: GroupDocs.Watermark for .NET API-referens
description: Initierar en ny instans avSpreadsheetPreviewOptionsgroupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions klass som gör att utgångsströmmen stängs.
type: docs
weight: 10
url: /sv/net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/spreadsheetpreviewoptions/
---
## SpreadsheetPreviewOptions(CreatePageStream) {#constructor}

Initierar en ny instans av[`SpreadsheetPreviewOptions`](../../spreadsheetpreviewoptions) klass som gör att utgångsströmmen stängs.

```csharp
public SpreadsheetPreviewOptions(CreatePageStream createPageStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Skapar en ström för en specifik förhandsvisning av sidan. |

### Se även

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [SpreadsheetPreviewOptions](../../spreadsheetpreviewoptions)
* namnutrymme [GroupDocs.Watermark.Options.Spreadsheet](../../spreadsheetpreviewoptions)
* hopsättning [GroupDocs.Watermark](../../../)

---

## SpreadsheetPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initierar en ny instans av[`SpreadsheetPreviewOptions`](../../spreadsheetpreviewoptions) klass som gör att utgångsströmmen returneras till klienten för vidare användning.

```csharp
public SpreadsheetPreviewOptions(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Skapar en ström för en specifik förhandsvisning av sidan. |
| releasePageStream | ReleasePageStream | Meddelar att genereringen av sidförhandsgranskningen är klar och hämtar utdataströmmen. |

### Se även

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [SpreadsheetPreviewOptions](../../spreadsheetpreviewoptions)
* namnutrymme [GroupDocs.Watermark.Options.Spreadsheet](../../spreadsheetpreviewoptions)
* hopsättning [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
