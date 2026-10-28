---
title: "EmailAttachmentCollection"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta una raccolta di allegati in un messaggio email."
type: docs
weight: 32
url: /it/java/com.groupdocs.watermark.contents/emailattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class EmailAttachmentCollection extends RemoveOnlyListBase<EmailAttachment>
```

Rappresenta una raccolta di allegati in un messaggio email.

Questa collezione contiene gli elementi di tipo `[EmailAttachment](../../com.groupdocs.watermark.contents/emailattachment)`.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [add(byte[] fileContent, String name)](#add-byte---java.lang.String-) | Aggiunge un allegato a `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`. |
|
|  | [removeFromDocument(EmailAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.EmailAttachment-) | <br /> |

|
### add(byte[] fileContent, String name) {#add-byte---java.lang.String-}
```
public final void add(byte[] fileContent, String name)
```


Aggiunge un allegato a `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fileContent | byte[] | Il contenuto del file da allegare. |
|
|  | name | java.lang.String | Il nome del file. |
|

### removeFromDocument(EmailAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.EmailAttachment-}
```
public void removeFromDocument(EmailAttachment item)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [EmailAttachment](../../com.groupdocs.watermark.contents/emailattachment) |  |

