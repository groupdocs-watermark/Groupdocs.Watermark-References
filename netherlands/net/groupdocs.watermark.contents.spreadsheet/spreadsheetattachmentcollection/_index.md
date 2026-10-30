---
title: "SpreadsheetAttachmentCollection"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt een verzameling bijlagen in een Excel-document voor."
type: docs
weight: 1110
url: /nl/net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/
---
## SpreadsheetAttachmentCollection class

Stelt een verzameling bijlagen in een Excel-document voor.

```csharp
public class SpreadsheetAttachmentCollection : RemoveOnlyListBase<SpreadsheetAttachment>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Haalt het aantal elementen op dat in de collectie zit. |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | Haalt een waarde op die aangeeft of de collectie alleen-lezen is. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Haalt het element op op de opgegeven index in de collectie. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddAttachment](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/addattachment)(byte[], string, byte[], double, double, double, double) | Voegt een bijlage toe aan het [`SpreadsheetWorksheet`](../spreadsheetworksheet). |
| [AddLink](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/addlink)(string, byte[], double, double, double, double) | Voegt een bijlage toe via een link (het document zal geen bijgevoegd bestandsinhoud bevatten). |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(SpreadsheetAttachment) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(SpreadsheetAttachment) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(SpreadsheetAttachment) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### Opmerkingen

Deze verzameling bevat de items van het type [`SpreadsheetAttachment`](../spreadsheetattachment).

### Zie ook

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [SpreadsheetAttachment](../spreadsheetattachment)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
