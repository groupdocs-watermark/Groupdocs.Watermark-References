---
title: SpreadsheetAttachmentCollection
second_title: .NET API Başvurusu için GroupDocs.Watermark
description: Bir Excel belgesindeki ekler koleksiyonunu temsil eder.
type: docs
weight: 1040
url: /tr/net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/
---
## SpreadsheetAttachmentCollection class

Bir Excel belgesindeki ekler koleksiyonunu temsil eder.

```csharp
public class SpreadsheetAttachmentCollection : RemoveOnlyListBase<SpreadsheetAttachment>
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Koleksiyonda bulunan öğelerin sayısını alır. |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | Koleksiyonun salt okunur olup olmadığını gösteren bir değer alır. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Koleksiyonda belirtilen dizindeki öğeyi alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddAttachment](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/addattachment)(byte[], string, byte[], double, double, double, double) | Dosyaya bir ek ekler.[`SpreadsheetWorksheet`](../spreadsheetworksheet) . |
| [AddLink](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/addlink)(string, byte[], double, double, double, double) | Bağlantı ile bir ek ekler (belge ekli dosya içeriğini içermez). |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(SpreadsheetAttachment) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(SpreadsheetAttachment) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(SpreadsheetAttachment) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### Notlar

Bu koleksiyon şunları içerir:[`SpreadsheetAttachment`](../spreadsheetattachment) yazın.

### Ayrıca bakınız

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [SpreadsheetAttachment](../spreadsheetattachment)
* ad alanı [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* toplantı [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->