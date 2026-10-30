---
title: "PdfAttachmentCollection"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt een verzameling bijlagen in een pdf-document voor."
type: docs
weight: 650
url: /nl/net/groupdocs.watermark.contents.pdf/pdfattachmentcollection/
---
## PdfAttachmentCollection class

Stelt een verzameling bijlagen in een pdf-document voor.

```csharp
public class PdfAttachmentCollection : RemoveOnlyListBase<PdfAttachment>
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
| [Add](../../groupdocs.watermark.contents.pdf/pdfattachmentcollection/add)(byte[], string, string) | Voegt een bijlage toe aan de [`PdfContent`](../pdfcontent). |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(PdfAttachment) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(PdfAttachment) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(PdfAttachment) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### Opmerkingen

Deze collectie bevat de items van het type [`PdfAttachment`](../pdfattachment).

### Zie ook

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [PdfAttachment](../pdfattachment)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
