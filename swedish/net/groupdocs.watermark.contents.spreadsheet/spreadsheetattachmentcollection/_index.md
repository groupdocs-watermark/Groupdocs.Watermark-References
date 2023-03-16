---
title: SpreadsheetAttachmentCollection
second_title: GroupDocs.Watermark for .NET API-referens
description: Representerar en samling bilagor i ett Exceldokument.
type: docs
weight: 1040
url: /sv/net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/
---
## SpreadsheetAttachmentCollection class

Representerar en samling bilagor i ett Excel-dokument.

```csharp
public class SpreadsheetAttachmentCollection : RemoveOnlyListBase<SpreadsheetAttachment>
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Hämtar antalet element som finns i samlingen. |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | Får ett värde som indikerar om samlingen är skrivskyddad. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Hämtar elementet vid angivet index i samlingen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddAttachment](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/addattachment)(byte[], string, byte[], double, double, double, double) | Lägger till en bilaga till[`SpreadsheetWorksheet`](../spreadsheetworksheet) . |
| [AddLink](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/addlink)(string, byte[], double, double, double, double) | Lägger till en bilaga via en länk (dokumentet kommer inte att innehålla bifogat filinnehåll). |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(SpreadsheetAttachment) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(SpreadsheetAttachment) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(SpreadsheetAttachment) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### Anmärkningar

Den här samlingen innehåller föremål från[`SpreadsheetAttachment`](../spreadsheetattachment) typ.

### Se även

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [SpreadsheetAttachment](../spreadsheetattachment)
* namnutrymme [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* hopsättning [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->