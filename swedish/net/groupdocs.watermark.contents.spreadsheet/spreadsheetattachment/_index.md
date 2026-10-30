---
title: "SpreadsheetAttachment"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar en fil som är bifogad till ett Excel-dokument."
type: docs
weight: 1100
url: /sv/net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/
---
## SpreadsheetAttachment class

Representerar en fil som är bifogad till ett Excel-dokument.

```csharp
public class SpreadsheetAttachment : Attachment, ITwoDObject
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/alternativetext) { get; set; } | Hämtar eller anger den beskrivande (alternativa) texten som är associerad med den bifogade filen. |
| override [Content](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/content) { get; set; } | Hämtar eller anger innehållet i den bifogade filen. |
| [Height](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/height) { get; set; } | Hämtar eller anger höjden på bilagans ram i punkter. |
| [IsLink](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/islink) { get; } | Hämtar ett värde som indikerar om innehållet endast innehåller en länk till filen. |
| [PreviewImageContent](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/previewimagecontent) { get; set; } | Hämtar eller anger förhandsgranskningsbilden för den bifogade filen som en byte-array. |
| [SourceFullName](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/sourcefullname) { get; } | Hämtar det fullständiga namnet på den bifogade filen. |
| [Width](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/width) { get; set; } | Hämtar eller anger bredden på bilagans ram i punkter. |
| [X](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/x) { get; set; } | Hämtar eller anger den horisontella förskjutningen av bilagans ram från kalkylbladets vänstra kant i punkter. |
| [Y](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/y) { get; set; } | Hämtar eller anger den vertikala förskjutningen av bilagans ram från kalkylbladets övre kant i punkter. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)() | Läser in ett innehåll från den bifogade filen. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions) | Läser in ett innehåll från den bifogade filen med de angivna inläsningsalternativen. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions, WatermarkerSettings) | Läser in ett innehåll från den bifogade filen med de angivna inläsningsalternativen och inställningarna. |
| [GetDocumentInfo](../../groupdocs.watermark.common/attachment/getdocumentinfo)() | Hämtar information om ett dokument som lagras i den bifogade filen. |

### Se även

* class [Attachment](../../groupdocs.watermark.common/attachment)
* interface [ITwoDObject](../../groupdocs.watermark.search/itwodobject)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
