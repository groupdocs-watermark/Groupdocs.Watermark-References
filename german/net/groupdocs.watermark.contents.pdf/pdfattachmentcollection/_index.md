---
title: "PdfAttachmentCollection"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt eine Sammlung von Anhängen in einem pdf-Dokument dar."
type: docs
weight: 650
url: /de/net/groupdocs.watermark.contents.pdf/pdfattachmentcollection/
---
## PdfAttachmentCollection class

Stellt eine Sammlung von Anhängen in einem pdf-Dokument dar.

```csharp
public class PdfAttachmentCollection : RemoveOnlyListBase<PdfAttachment>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Liefert die Anzahl der in der Sammlung enthaltenen Elemente. |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | Liefert einen Wert, der angibt, ob die Sammlung schreibgeschützt ist. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Liefert das Element am angegebenen Index in der Sammlung. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.pdf/pdfattachmentcollection/add)(byte[], string, string) | Fügt dem [`PdfContent`](../pdfcontent) einen Anhang hinzu. |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(PdfAttachment) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(PdfAttachment) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(PdfAttachment) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### Hinweise

Diese Sammlung enthält Elemente des Typs [`PdfAttachment`](../pdfattachment).

### Siehe auch

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [PdfAttachment](../pdfattachment)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
