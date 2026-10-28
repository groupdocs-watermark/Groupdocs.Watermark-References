---
title: "EmailEmbeddedObjectCollection"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili koleksi objek yang disematkan dalam pesan email."
type: docs
weight: 36
url: /id/java/com.groupdocs.watermark.contents/emailembeddedobjectcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class EmailEmbeddedObjectCollection extends RemoveOnlyListBase<EmailEmbeddedObject>
```

Mewakili koleksi objek yang disematkan dalam pesan email.

Koleksi ini berisi item-item dari tipe `[EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject)`.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [add(byte[] fileContent, String name)](#add-byte---java.lang.String-) | Menambahkan sumber daya tersemat ke `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`. |
|
|  | [removeFromDocument(EmailEmbeddedObject item)](#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-) | <br /> |

|
### add(byte[] fileContent, String name) {#add-byte---java.lang.String-}
```
public final void add(byte[] fileContent, String name)
```


Menambahkan sumber daya tersemat ke `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fileContent | byte[] | Konten file yang akan ditambahkan. |
|
|  | name | java.lang.String | Nama file. |
|

### removeFromDocument(EmailEmbeddedObject item) {#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-}
```
public void removeFromDocument(EmailEmbeddedObject item)
```


<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject) |  |

