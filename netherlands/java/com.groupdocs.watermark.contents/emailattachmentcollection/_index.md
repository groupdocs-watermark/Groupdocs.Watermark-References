---
title: "EmailAttachmentCollection"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een verzameling bijlagen in een e-mailbericht voor."
type: docs
weight: 32
url: /nl/java/com.groupdocs.watermark.contents/emailattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class EmailAttachmentCollection extends RemoveOnlyListBase<EmailAttachment>
```

Stelt een verzameling bijlagen in een e-mailbericht voor.

Deze collectie bevat items van het type `[EmailAttachment](../../com.groupdocs.watermark.contents/emailattachment)`.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [add(byte[] fileContent, String name)](#add-byte---java.lang.String-) | Voegt een bijlage toe aan de `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`. |
|
|  | [removeFromDocument(EmailAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.EmailAttachment-) | <br /> |

|
### add(byte[] fileContent, String name) {#add-byte---java.lang.String-}
```
public final void add(byte[] fileContent, String name)
```


Voegt een bijlage toe aan de `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fileContent | byte[] | De inhoud van het bestand dat moet worden bijgevoegd. |
|
|  | name | java.lang.String | De naam van het bestand. |
|

### removeFromDocument(EmailAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.EmailAttachment-}
```
public void removeFromDocument(EmailAttachment item)
```


<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [EmailAttachment](../../com.groupdocs.watermark.contents/emailattachment) |  |

