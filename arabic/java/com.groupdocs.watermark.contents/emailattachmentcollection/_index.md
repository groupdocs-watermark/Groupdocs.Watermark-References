---
title: "EmailAttachmentCollection"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل مجموعة من المرفقات في رسالة بريد إلكتروني."
type: docs
weight: 32
url: /ar/java/com.groupdocs.watermark.contents/emailattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class EmailAttachmentCollection extends RemoveOnlyListBase<EmailAttachment>
```

يمثل مجموعة من المرفقات في رسالة بريد إلكتروني.

تحتوي هذه المجموعة على العناصر من نوع `[EmailAttachment](../../com.groupdocs.watermark.contents/emailattachment)`.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [add(byte[] fileContent, String name)](#add-byte---java.lang.String-) | يضيف مرفقًا إلى `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`. |
|
|  | [removeFromDocument(EmailAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.EmailAttachment-) | <br /> |

|
### add(byte[] fileContent, String name) {#add-byte---java.lang.String-}
```
public final void add(byte[] fileContent, String name)
```


يضيف مرفقًا إلى `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileContent | byte[] | محتوى الملف المراد إرفاقه. |
|
|  | name | java.lang.String | اسم الملف. |
|

### removeFromDocument(EmailAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.EmailAttachment-}
```
public void removeFromDocument(EmailAttachment item)
```


<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [EmailAttachment](../../com.groupdocs.watermark.contents/emailattachment) |  |

