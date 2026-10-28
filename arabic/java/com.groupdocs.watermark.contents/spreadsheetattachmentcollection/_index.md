---
title: "SpreadsheetAttachmentCollection"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل مجموعة من المرفقات في مستند Excel."
type: docs
weight: 102
url: /ar/java/com.groupdocs.watermark.contents/spreadsheetattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class SpreadsheetAttachmentCollection extends RemoveOnlyListBase<SpreadsheetAttachment>
```

يمثل مجموعة من المرفقات في مستند Excel.

تحتوي هذه المجموعة على عناصر من النوع `[SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment)`.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addAttachment-byte---java.lang.String-byte---double-double-double-double-) | يضيف مرفقًا إلى `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`. |
|
|  | [addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addLink-java.lang.String-byte---double-double-double-double-) | يضيف مرفقًا عبر رابط (لن يحتوي المستند على محتوى الملف المرفق). |
|
|  | [removeFromDocument(SpreadsheetAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-) | <br /> |

|
### addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addAttachment-byte---java.lang.String-byte---double-double-double-double-}
```
public final void addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


يضيف مرفقًا إلى `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileContent | byte[] | محتوى الملف المراد إرفاقه. |
|
|  | sourceFullName | java.lang.String | الاسم الكامل للملف المرفق (يُستخدم الامتداد لتحديد التطبيق المناسب لفتح الملف). |
|
|  | previewImageContent | byte[] | صورة معاينة الملف المرفق كمصفوفة بايت. |
|
|  | x | double | الإحداثي السيني لإطار المرفق (بالنقاط). |
|
|  | y | double | الإحداثي الصادي لإطار المرفق (بالنقاط). |
|
|  | العرض | double | عرض إطار المرفق بالنقاط. |
|
|  | الارتفاع | double | ارتفاع إطار المرفق بالنقاط. |
|

### addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addLink-java.lang.String-byte---double-double-double-double-}
```
public final void addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


يضيف مرفقًا عبر رابط (لن يحتوي المستند على محتوى الملف المرفق).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | sourceFullName | java.lang.String | مسار الملف المرتبط. |
|
|  | previewImageContent | byte[] | صورة معاينة الملف المرفق كمصفوفة بايت. |
|
|  | x | double | الإحداثي السيني لإطار المرفق (بالنقاط). |
|
|  | y | double | الإحداثي الصادي لإطار المرفق (بالنقاط). |
|
|  | العرض | double | عرض إطار المرفق بالنقاط. |
|
|  | الارتفاع | double | ارتفاع إطار المرفق بالنقاط. |
|

### removeFromDocument(SpreadsheetAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-}
```
public void removeFromDocument(SpreadsheetAttachment item)
```


<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment) |  |

