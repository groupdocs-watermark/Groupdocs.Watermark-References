---
title: "EmailAttachmentCollection"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine Sammlung von Anhängen in einer E-Mail-Nachricht dar."
type: docs
weight: 32
url: /de/java/com.groupdocs.watermark.contents/emailattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class EmailAttachmentCollection extends RemoveOnlyListBase<EmailAttachment>
```

Stellt eine Sammlung von Anhängen in einer E-Mail-Nachricht dar.

Diese Sammlung enthält Elemente des Typs `[EmailAttachment](../../com.groupdocs.watermark.contents/emailattachment)`.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [add(byte[] fileContent, String name)](#add-byte---java.lang.String-) | Fügt einen Anhang zum `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)` hinzu. |
|
|  | [removeFromDocument(EmailAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.EmailAttachment-) | <br /> |

|
### add(byte[] fileContent, String name) {#add-byte---java.lang.String-}
```
public final void add(byte[] fileContent, String name)
```


Fügt einen Anhang zum `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)` hinzu.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileContent | byte[] | Der Inhalt der anzuhängenden Datei. |
|
|  | name | java.lang.String | Der Name der Datei. |
|

### removeFromDocument(EmailAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.EmailAttachment-}
```
public void removeFromDocument(EmailAttachment item)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [EmailAttachment](../../com.groupdocs.watermark.contents/emailattachment) |  |

