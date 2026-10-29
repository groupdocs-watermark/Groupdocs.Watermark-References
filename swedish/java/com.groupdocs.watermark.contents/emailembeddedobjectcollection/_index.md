---
title: "EmailEmbeddedObjectCollection"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar en samling av inbäddade objekt i ett e‑postmeddelande."
type: docs
weight: 36
url: /sv/java/com.groupdocs.watermark.contents/emailembeddedobjectcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class EmailEmbeddedObjectCollection extends RemoveOnlyListBase<EmailEmbeddedObject>
```

Representerar en samling av inbäddade objekt i ett e‑postmeddelande.

Denna samling innehåller objekt av typen `[EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject)`.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [add(byte[] fileContent, String name)](#add-byte---java.lang.String-) | Lägger till en inbäddad resurs till `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`. |
|
|  | [removeFromDocument(EmailEmbeddedObject item)](#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-) | <br /> |

|
### add(byte[] fileContent, String name) {#add-byte---java.lang.String-}
```
public final void add(byte[] fileContent, String name)
```


Lägger till en inbäddad resurs till `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileContent | byte[] | Innehållet i filen som ska läggas till. |
|
|  | name | java.lang.String | Filens namn. |
|

### removeFromDocument(EmailEmbeddedObject item) {#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-}
```
public void removeFromDocument(EmailEmbeddedObject item)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject) |  |

