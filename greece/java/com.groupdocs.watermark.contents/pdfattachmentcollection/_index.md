---
title: "PdfAttachmentCollection"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αναπαριστά μια συλλογή συνημμένων σε ένα pdf έγγραφο."
type: docs
weight: 59
url: /el/java/com.groupdocs.watermark.contents/pdfattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class PdfAttachmentCollection extends RemoveOnlyListBase<PdfAttachment>
```

Αναπαριστά μια συλλογή συνημμένων σε ένα pdf έγγραφο.

Αυτή η συλλογή περιέχει στοιχεία τύπου `[PdfAttachment](../../com.groupdocs.watermark.contents/pdfattachment)`.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [add(byte[] fileContent, String name, String description)](#add-byte---java.lang.String-java.lang.String-) | Προσθέτει ένα συνημμένο στο `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`. |
|
|  | [removeFromDocument(PdfAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.PdfAttachment-) | <br /> |

|
### add(byte[] fileContent, String name, String description) {#add-byte---java.lang.String-java.lang.String-}
```
public final void add(byte[] fileContent, String name, String description)
```


Προσθέτει ένα συνημμένο στο `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileContent | byte[] | Το περιεχόμενο του αρχείου που θα προσαρτηθεί. |
|
|  | name | java.lang.String | Το όνομα του αρχείου. |
|
|  | description | java.lang.String | Η περιγραφή του αρχείου. |
|

### removeFromDocument(PdfAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.PdfAttachment-}
```
public void removeFromDocument(PdfAttachment item)
```


<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [PdfAttachment](../../com.groupdocs.watermark.contents/pdfattachment) |  |

