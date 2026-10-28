---
title: "EmailEmbeddedObjectCollection"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل مجموعة من الكائنات المدمجة في رسالة بريد إلكتروني."
type: docs
weight: 36
url: /ar/java/com.groupdocs.watermark.contents/emailembeddedobjectcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class EmailEmbeddedObjectCollection extends RemoveOnlyListBase<EmailEmbeddedObject>
```

يمثل مجموعة من الكائنات المدمجة في رسالة بريد إلكتروني.

تحتوي هذه المجموعة على عناصر من النوع `[EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject)`.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [add(byte[] fileContent, String name)](#add-byte---java.lang.String-) | يضيف موردًا مضمّنًا إلى `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`. |
|
|  | [removeFromDocument(EmailEmbeddedObject item)](#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-) | <br /> |

|
### add(byte[] fileContent, String name) {#add-byte---java.lang.String-}
```
public final void add(byte[] fileContent, String name)
```


يضيف موردًا مضمّنًا إلى `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileContent | byte[] | محتوى الملف الذي سيتم إضافته. |
|
|  | name | java.lang.String | اسم الملف. |
|

### removeFromDocument(EmailEmbeddedObject item) {#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-}
```
public void removeFromDocument(EmailEmbeddedObject item)
```


<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject) |  |

