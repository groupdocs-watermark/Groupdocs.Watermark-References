---
title: "PdfAttachmentCollection"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar en samling av bilagor i ett pdf-dokument."
type: docs
weight: 59
url: /sv/java/com.groupdocs.watermark.contents/pdfattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class PdfAttachmentCollection extends RemoveOnlyListBase<PdfAttachment>
```

Representerar en samling av bilagor i ett pdf-dokument.

Denna samling innehåller objekt av typen `[PdfAttachment](../../com.groupdocs.watermark.contents/pdfattachment)`.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [add(byte[] fileContent, String name, String description)](#add-byte---java.lang.String-java.lang.String-) | Lägger till en bilaga till `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`. |
|
|  | [removeFromDocument(PdfAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.PdfAttachment-) | <br /> |

|
### add(byte[] fileContent, String name, String description) {#add-byte---java.lang.String-java.lang.String-}
```
public final void add(byte[] fileContent, String name, String description)
```


Lägger till en bilaga till `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileContent | byte[] | Innehållet i filen som ska bifogas. |
|
|  | name | java.lang.String | Filens namn. |
|
|  | description | java.lang.String | Filens beskrivning. |
|

### removeFromDocument(PdfAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.PdfAttachment-}
```
public void removeFromDocument(PdfAttachment item)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [PdfAttachment](../../com.groupdocs.watermark.contents/pdfattachment) |  |

