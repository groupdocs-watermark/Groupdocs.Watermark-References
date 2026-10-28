---
title: "PdfAttachmentCollection"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een verzameling bijlagen in een pdf-document voor."
type: docs
weight: 59
url: /nl/java/com.groupdocs.watermark.contents/pdfattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class PdfAttachmentCollection extends RemoveOnlyListBase<PdfAttachment>
```

Stelt een verzameling bijlagen in een pdf-document voor.

Deze collectie bevat de items van het type `[PdfAttachment](../../com.groupdocs.watermark.contents/pdfattachment)`.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [add(byte[] fileContent, String name, String description)](#add-byte---java.lang.String-java.lang.String-) | Voegt een bijlage toe aan de `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`. |
|
|  | [removeFromDocument(PdfAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.PdfAttachment-) | <br /> |

|
### add(byte[] fileContent, String name, String description) {#add-byte---java.lang.String-java.lang.String-}
```
public final void add(byte[] fileContent, String name, String description)
```


Voegt een bijlage toe aan de `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fileContent | byte[] | De inhoud van het bestand dat moet worden bijgevoegd. |
|
|  | name | java.lang.String | De naam van het bestand. |
|
|  | description | java.lang.String | De beschrijving van het bestand. |
|

### removeFromDocument(PdfAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.PdfAttachment-}
```
public void removeFromDocument(PdfAttachment item)
```


<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [PdfAttachment](../../com.groupdocs.watermark.contents/pdfattachment) |  |

