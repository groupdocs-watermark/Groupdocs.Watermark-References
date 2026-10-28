---
title: "EmailAttachmentBase"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "ईमेल अटैचमेंट्स के लिए एक बेस क्लास प्रदान करता है।"
type: docs
weight: 31
url: /hi/java/com.groupdocs.watermark.contents/emailattachmentbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)
```
public abstract class EmailAttachmentBase extends Attachment
```

ईमेल अटैचमेंट्स के लिए एक बेस क्लास प्रदान करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getContentId()](#getContentId--) | इस `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` का कंटेंट आईडी प्राप्त करता है। |
|
|  | [getMediaType()](#getMediaType--) | इस `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` का मीडिया प्रकार प्राप्त करता है। |
|
|  | [getContent()](#getContent--) | संलग्न फ़ाइल की सामग्री प्राप्त करता है। |
|
|  | [setContent(byte[] value)](#setContent-byte---) | संलग्न फ़ाइल की सामग्री सेट करता है। |
|
| [getContentStream()](#getContentStream--) |  |
| [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) |  |
### getContentId() {#getContentId--}
```
public final String getContentId()
```


इस `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` का कंटेंट आईडी प्राप्त करता है।


**Returns:**
java.lang.String - इस `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` का कंटेंट आईडी।

### getMediaType() {#getMediaType--}
```
public final String getMediaType()
```


इस `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` का मीडिया प्रकार प्राप्त करता है।


**Returns:**
java.lang.String - इस `<[EmailAttachmentBase](../../com.groupdocs.watermark.contents/emailattachmentbase)` का मीडिया प्रकार।

### getContent() {#getContent--}
```
public byte[] getContent()
```


संलग्न फ़ाइल की सामग्री प्राप्त करता है।


**Returns:**
byte[] - संलग्न फ़ाइल की सामग्री।

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


संलग्न फ़ाइल की सामग्री सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | byte[] | संलग्न फ़ाइल की सामग्री। |
|

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


संलग्न फ़ाइल से स्ट्रीम प्राप्त करता है।


**Returns:**
com.aspose.ms.System.IO.Stream
### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


स्ट्रीम से संलग्न फ़ाइल को अपडेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

