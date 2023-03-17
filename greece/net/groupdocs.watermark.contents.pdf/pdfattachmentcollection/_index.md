---
title: PdfAttachmentCollection
second_title: GroupDocs.Watermark για Αναφορά API .NET
description: Αντιπροσωπεύει μια συλλογή συνημμένων σε ένα έγγραφο pdf.
type: docs
weight: 600
url: /el/net/groupdocs.watermark.contents.pdf/pdfattachmentcollection/
---
## PdfAttachmentCollection class

Αντιπροσωπεύει μια συλλογή συνημμένων σε ένα έγγραφο pdf.

```csharp
public class PdfAttachmentCollection : RemoveOnlyListBase<PdfAttachment>
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| virtual [Count](../../groupdocs.watermark.common/readonlylistbase-1/count) { get; } | Λαμβάνει τον αριθμό των στοιχείων που περιέχονται στη συλλογή. |
| override [IsReadOnly](../../groupdocs.watermark.common/removeonlylistbase-1/isreadonly) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η συλλογή είναι μόνο για ανάγνωση. |
| virtual [Item](../../groupdocs.watermark.common/readonlylistbase-1/item) { get; } | Παίρνει το στοιχείο στο καθορισμένο ευρετήριο της συλλογής. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.pdf/pdfattachmentcollection/add)(byte[], string, string) | Προσθέτει ένα συνημμένο στο[`PdfContent`](../pdfcontent) . |
| [Clear](../../groupdocs.watermark.common/removeonlylistbase-1/clear)() |  |
| virtual [Contains](../../groupdocs.watermark.common/readonlylistbase-1/contains)(PdfAttachment) |  |
| virtual [GetEnumerator](../../groupdocs.watermark.common/readonlylistbase-1/getenumerator)() |  |
| virtual [IndexOf](../../groupdocs.watermark.common/readonlylistbase-1/indexof)(PdfAttachment) |  |
| [Remove](../../groupdocs.watermark.common/removeonlylistbase-1/remove)(PdfAttachment) |  |
| [RemoveAt](../../groupdocs.watermark.common/removeonlylistbase-1/removeat)(int) |  |

### Παρατηρήσεις

Αυτή η συλλογή περιέχει τα στοιχεία του[`PdfAttachment`](../pdfattachment) τύπος.

### Δείτε επίσης

* class [RemoveOnlyListBase&lt;T&gt;](../../groupdocs.watermark.common/removeonlylistbase-1)
* class [PdfAttachment](../pdfattachment)
* χώρος ονομάτων [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* συνέλευση [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->