---
title: "EmailAttachmentCollection"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "E-posta mesajındaki eklerin bir koleksiyonunu temsil eder."
type: docs
weight: 32
url: /tr/java/com.groupdocs.watermark.contents/emailattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class EmailAttachmentCollection extends RemoveOnlyListBase<EmailAttachment>
```

E-posta mesajındaki eklerin bir koleksiyonunu temsil eder.

Bu koleksiyon, `[EmailAttachment](../../com.groupdocs.watermark.contents/emailattachment)` tipindeki öğeleri içerir.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [add(byte[] fileContent, String name)](#add-byte---java.lang.String-) | `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)` öğesine bir ek ekler. |
|
|  | [removeFromDocument(EmailAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.EmailAttachment-) | <br /> |

|
### add(byte[] fileContent, String name) {#add-byte---java.lang.String-}
```
public final void add(byte[] fileContent, String name)
```


`[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)` öğesine bir ek ekler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fileContent | byte[] | Eklenecek dosyanın içeriği. |
|
|  | name | java.lang.String | Dosyanın adı. |
|

### removeFromDocument(EmailAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.EmailAttachment-}
```
public void removeFromDocument(EmailAttachment item)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [EmailAttachment](../../com.groupdocs.watermark.contents/emailattachment) |  |

