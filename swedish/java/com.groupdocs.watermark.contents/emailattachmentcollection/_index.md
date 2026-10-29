---
title: "EmailAttachmentCollection"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar en samling av bilagor i ett e‑postmeddelande."
type: docs
weight: 32
url: /sv/java/com.groupdocs.watermark.contents/emailattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class EmailAttachmentCollection extends RemoveOnlyListBase<EmailAttachment>
```

Representerar en samling av bilagor i ett e‑postmeddelande.

Denna samling innehåller objekt av typen `[EmailAttachment](../../com.groupdocs.watermark.contents/emailattachment)`.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [add(byte[] fileContent, String name)](#add-byte---java.lang.String-) | Lägger till en bilaga till `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`. |
|
|  | [removeFromDocument(EmailAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.EmailAttachment-) | <br /> |

|
### add(byte[] fileContent, String name) {#add-byte---java.lang.String-}
```
public final void add(byte[] fileContent, String name)
```


Lägger till en bilaga till `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileContent | byte[] | Innehållet i filen som ska bifogas. |
|
|  | name | java.lang.String | Filens namn. |
|

### removeFromDocument(EmailAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.EmailAttachment-}
```
public void removeFromDocument(EmailAttachment item)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [EmailAttachment](../../com.groupdocs.watermark.contents/emailattachment) |  |

