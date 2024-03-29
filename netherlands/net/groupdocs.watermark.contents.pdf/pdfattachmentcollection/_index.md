---
title: PdfAttachmentCollection
second_title: GroupDocs.Watermark voor .NET API-referentie
description: Vertegenwoordigt een verzameling bijlagen in een pdfdocument.
type: docs
weight: 600
url: /nl/net/groupdocs.watermark.contents.pdf/pdfattachmentcollection/
---
## PdfAttachmentCollection class

Vertegenwoordigt een verzameling bijlagen in een pdf-document.

```csharp
public class PdfAttachmentCollection : RemoveOnlyListBase<PdfAttachment>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Krijgt het aantal elementen in de collectie. |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | Krijgt een waarde die aangeeft of de verzameling alleen-lezen is. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Haalt het element op bij de gespecificeerde index in de verzameling. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.pdf/pdfattachmentcollection/add)(byte[], string, string) | Voegt een bijlage toe aan het[`PdfContent`](../pdfcontent) . |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(PdfAttachment) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(PdfAttachment) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(PdfAttachment) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### Opmerkingen

Deze collectie bevat de items van[`PdfAttachment`](../pdfattachment) type.

### Zie ook

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [PdfAttachment](../pdfattachment)
* naamruimte [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* montage [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
