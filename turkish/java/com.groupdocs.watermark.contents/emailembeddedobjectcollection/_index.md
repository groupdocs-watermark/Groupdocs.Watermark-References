---
title: "EmailEmbeddedObjectCollection"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "E-posta mesajındaki gömülü nesnelerin bir koleksiyonunu temsil eder."
type: docs
weight: 36
url: /tr/java/com.groupdocs.watermark.contents/emailembeddedobjectcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class EmailEmbeddedObjectCollection extends RemoveOnlyListBase<EmailEmbeddedObject>
```

E-posta mesajındaki gömülü nesnelerin bir koleksiyonunu temsil eder.

Bu koleksiyon, `[EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject)` türündeki öğeleri içerir.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [add(byte[] fileContent, String name)](#add-byte---java.lang.String-) | `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)` öğesine gömülü bir kaynak ekler. |
|
|  | [removeFromDocument(EmailEmbeddedObject item)](#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-) | <br /> |

|
### add(byte[] fileContent, String name) {#add-byte---java.lang.String-}
```
public final void add(byte[] fileContent, String name)
```


`[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)` öğesine gömülü bir kaynak ekler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fileContent | byte[] | Eklenecek dosyanın içeriği. |
|
|  | name | java.lang.String | Dosyanın adı. |
|

### removeFromDocument(EmailEmbeddedObject item) {#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-}
```
public void removeFromDocument(EmailEmbeddedObject item)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject) |  |

