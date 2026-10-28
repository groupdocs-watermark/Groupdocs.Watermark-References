---
title: "EmailAttachmentCollection"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει μια συλλογή συνημμένων σε ένα μήνυμα email."
type: docs
weight: 32
url: /el/java/com.groupdocs.watermark.contents/emailattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class EmailAttachmentCollection extends RemoveOnlyListBase<EmailAttachment>
```

Αντιπροσωπεύει μια συλλογή συνημμένων σε ένα μήνυμα email.

Αυτή η συλλογή περιέχει τα στοιχεία τύπου `[EmailAttachment](../../com.groupdocs.watermark.contents/emailattachment)`.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [add(byte[] fileContent, String name)](#add-byte---java.lang.String-) | Προσθέτει ένα συνημμένο στο `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`. |
|
|  | [removeFromDocument(EmailAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.EmailAttachment-) | <br /> |

|
### add(byte[] fileContent, String name) {#add-byte---java.lang.String-}
```
public final void add(byte[] fileContent, String name)
```


Προσθέτει ένα συνημμένο στο `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileContent | byte[] | Το περιεχόμενο του αρχείου που θα προσαρτηθεί. |
|
|  | name | java.lang.String | Το όνομα του αρχείου. |
|

### removeFromDocument(EmailAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.EmailAttachment-}
```
public void removeFromDocument(EmailAttachment item)
```


<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [EmailAttachment](../../com.groupdocs.watermark.contents/emailattachment) |  |

