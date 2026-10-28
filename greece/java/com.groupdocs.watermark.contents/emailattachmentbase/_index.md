---
title: "EmailAttachmentBase"
second_title: "GroupDocs.Watermark για Java API Reference"
description: "Παρέχει μια βασική κλάση για συνημμένα email."
type: docs
weight: 31
url: /el/java/com.groupdocs.watermark.contents/emailattachmentbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)
```
public abstract class EmailAttachmentBase extends Attachment
```

Παρέχει μια βασική κλάση για συνημμένα email.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getContentId()](#getContentId--) | Αποκτά το αναγνωριστικό περιεχομένου αυτού του `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`. |
|
|  | [getMediaType()](#getMediaType--) | Αποκτά τον τύπο μέσου αυτού του `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`. |
|
|  | [getContent()](#getContent--) | Λαμβάνει το περιεχόμενο του συνημμένου αρχείου. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Ορίζει το περιεχόμενο του συνημμένου αρχείου. |
|
| [getContentStream()](#getContentStream--) |  |
| [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) |  |
### getContentId() {#getContentId--}
```
public final String getContentId()
```


Αποκτά το αναγνωριστικό περιεχομένου αυτού του `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.


**Returns:**
java.lang.String - Το αναγνωριστικό περιεχομένου αυτού του `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.

### getMediaType() {#getMediaType--}
```
public final String getMediaType()
```


Αποκτά τον τύπο μέσου αυτού του `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.


**Returns:**
java.lang.String - Ο τύπος μέσου αυτού του `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)`.

### getContent() {#getContent--}
```
public byte[] getContent()
```


Λαμβάνει το περιεχόμενο του συνημμένου αρχείου.


**Returns:**
byte[] - Το περιεχόμενο του συνημμένου αρχείου.

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Ορίζει το περιεχόμενο του συνημμένου αρχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | byte[] | Το περιεχόμενο του συνημμένου αρχείου. |
|

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


Λαμβάνει μια ροή από το συνημμένο αρχείο.


**Returns:**
com.aspose.ms.System.IO.Stream
### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


Ενημερώνει το συνημμένο αρχείο από μια ροή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | com.aspose.ms.System.IO.Stream |  |

