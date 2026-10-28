---
title: "EmailEmbeddedObjectCollection"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een verzameling ingebedde objecten in een e-mailbericht voor."
type: docs
weight: 36
url: /nl/java/com.groupdocs.watermark.contents/emailembeddedobjectcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class EmailEmbeddedObjectCollection extends RemoveOnlyListBase<EmailEmbeddedObject>
```

Stelt een verzameling ingebedde objecten in een e-mailbericht voor.

Deze collectie bevat de items van het type `[EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject)`.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [add(byte[] fileContent, String name)](#add-byte---java.lang.String-) | Voegt een ingebedde bron toe aan de `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`. |
|
|  | [removeFromDocument(EmailEmbeddedObject item)](#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-) | <br /> |

|
### add(byte[] fileContent, String name) {#add-byte---java.lang.String-}
```
public final void add(byte[] fileContent, String name)
```


Voegt een ingebedde bron toe aan de `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fileContent | byte[] | De inhoud van het toe te voegen bestand. |
|
|  | name | java.lang.String | De naam van het bestand. |
|

### removeFromDocument(EmailEmbeddedObject item) {#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-}
```
public void removeFromDocument(EmailEmbeddedObject item)
```


<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject) |  |

