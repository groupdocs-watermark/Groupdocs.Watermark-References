---
title: "EmailAttachmentCollection"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "ईमेल संदेश में अटैचमेंट्स के संग्रह का प्रतिनिधित्व करता है।"
type: docs
weight: 32
url: /hi/java/com.groupdocs.watermark.contents/emailattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class EmailAttachmentCollection extends RemoveOnlyListBase<EmailAttachment>
```

ईमेल संदेश में अटैचमेंट्स के संग्रह का प्रतिनिधित्व करता है।

यह संग्रह `[EmailAttachment](../../com.groupdocs.watermark.contents/emailattachment)` प्रकार के आइटम्स रखता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [add(byte[] fileContent, String name)](#add-byte---java.lang.String-) | `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)` में एक अटैचमेंट जोड़ता है। |
|
|  | [removeFromDocument(EmailAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.EmailAttachment-) | <br /> |

|
### add(byte[] fileContent, String name) {#add-byte---java.lang.String-}
```
public final void add(byte[] fileContent, String name)
```


`[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)` में एक अटैचमेंट जोड़ता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | fileContent | byte[] | संलग्न की जाने वाली फ़ाइल की सामग्री। |
|
|  | name | java.lang.String | फ़ाइल का नाम। |
|

### removeFromDocument(EmailAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.EmailAttachment-}
```
public void removeFromDocument(EmailAttachment item)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [EmailAttachment](../../com.groupdocs.watermark.contents/emailattachment) |  |

