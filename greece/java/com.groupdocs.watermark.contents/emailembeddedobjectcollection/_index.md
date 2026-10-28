---
title: "EmailEmbeddedObjectCollection"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Αντιπροσωπεύει μια συλλογή ενσωματωμένων αντικειμένων σε ένα μήνυμα email."
type: docs
weight: 36
url: /el/java/com.groupdocs.watermark.contents/emailembeddedobjectcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class EmailEmbeddedObjectCollection extends RemoveOnlyListBase<EmailEmbeddedObject>
```

Αντιπροσωπεύει μια συλλογή ενσωματωμένων αντικειμένων σε ένα μήνυμα email.

Αυτή η συλλογή περιέχει τα στοιχεία του τύπου `[EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject)`.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [add(byte[] fileContent, String name)](#add-byte---java.lang.String-) | Προσθέτει έναν ενσωματωμένο πόρο στο `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`. |
|
|  | [removeFromDocument(EmailEmbeddedObject item)](#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-) | <br /> |

|
### add(byte[] fileContent, String name) {#add-byte---java.lang.String-}
```
public final void add(byte[] fileContent, String name)
```


Προσθέτει έναν ενσωματωμένο πόρο στο `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)`.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileContent | byte[] | Το περιεχόμενο του αρχείου που θα προστεθεί. |
|
|  | name | java.lang.String | Το όνομα του αρχείου. |
|

### removeFromDocument(EmailEmbeddedObject item) {#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-}
```
public void removeFromDocument(EmailEmbeddedObject item)
```


<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject) |  |

