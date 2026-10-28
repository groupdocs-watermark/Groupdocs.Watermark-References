---
title: "PdfAttachmentCollection"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل مجموعة من المرفقات في مستند PDF."
type: docs
weight: 59
url: /ar/java/com.groupdocs.watermark.contents/pdfattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class PdfAttachmentCollection extends RemoveOnlyListBase<PdfAttachment>
```

يمثل مجموعة من المرفقات في مستند PDF.

هذه المجموعة تحتوي على عناصر من النوع `[PdfAttachment](../../com.groupdocs.watermark.contents/pdfattachment)`.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [add(byte[] fileContent, String name, String description)](#add-byte---java.lang.String-java.lang.String-) | يضيف مرفقًا إلى `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`. |
|
|  | [removeFromDocument(PdfAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.PdfAttachment-) | <br /> |

|
### add(byte[] fileContent, String name, String description) {#add-byte---java.lang.String-java.lang.String-}
```
public final void add(byte[] fileContent, String name, String description)
```


يضيف مرفقًا إلى `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileContent | byte[] | محتوى الملف المراد إرفاقه. |
|
|  | name | java.lang.String | اسم الملف. |
|
|  | description | java.lang.String | وصف الملف. |
|

### removeFromDocument(PdfAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.PdfAttachment-}
```
public void removeFromDocument(PdfAttachment item)
```


<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [PdfAttachment](../../com.groupdocs.watermark.contents/pdfattachment) |  |

