---
title: "PdfAttachmentCollection"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "PDF belgesindeki eklerin bir koleksiyonunu temsil eder."
type: docs
weight: 59
url: /tr/java/com.groupdocs.watermark.contents/pdfattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class PdfAttachmentCollection extends RemoveOnlyListBase<PdfAttachment>
```

PDF belgesindeki eklerin bir koleksiyonunu temsil eder.

Bu koleksiyon, `[PdfAttachment](../../com.groupdocs.watermark.contents/pdfattachment)` türündeki öğeleri içerir.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [add(byte[] fileContent, String name, String description)](#add-byte---java.lang.String-java.lang.String-) | `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`'e bir ek ekler. |
|
|  | [removeFromDocument(PdfAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.PdfAttachment-) | <br /> |

|
### add(byte[] fileContent, String name, String description) {#add-byte---java.lang.String-java.lang.String-}
```
public final void add(byte[] fileContent, String name, String description)
```


`[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`'e bir ek ekler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fileContent | byte[] | Eklenecek dosyanın içeriği. |
|
|  | name | java.lang.String | Dosyanın adı. |
|
|  | description | java.lang.String | Dosyanın açıklaması. |
|

### removeFromDocument(PdfAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.PdfAttachment-}
```
public void removeFromDocument(PdfAttachment item)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [PdfAttachment](../../com.groupdocs.watermark.contents/pdfattachment) |  |

