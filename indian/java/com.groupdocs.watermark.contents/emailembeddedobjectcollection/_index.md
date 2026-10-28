---
title: "EmailEmbeddedObjectCollection"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "ईमेल संदेश में एम्बेडेड ऑब्जेक्ट्स के संग्रह का प्रतिनिधित्व करता है।"
type: docs
weight: 36
url: /hi/java/com.groupdocs.watermark.contents/emailembeddedobjectcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class EmailEmbeddedObjectCollection extends RemoveOnlyListBase<EmailEmbeddedObject>
```

ईमेल संदेश में एम्बेडेड ऑब्जेक्ट्स के संग्रह का प्रतिनिधित्व करता है।

यह संग्रह `[EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject)` प्रकार की वस्तुओं को शामिल करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [add(byte[] fileContent, String name)](#add-byte---java.lang.String-) | एक एम्बेडेड संसाधन को `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)` में जोड़ता है। |
|
|  | [removeFromDocument(EmailEmbeddedObject item)](#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-) | <br /> |

|
### add(byte[] fileContent, String name) {#add-byte---java.lang.String-}
```
public final void add(byte[] fileContent, String name)
```


एक एम्बेडेड संसाधन को `[EmailContent](../../com.groupdocs.watermark.contents/emailcontent)` में जोड़ता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | fileContent | byte[] | जोड़ी जाने वाली फ़ाइल की सामग्री। |
|
|  | name | java.lang.String | फ़ाइल का नाम। |
|

### removeFromDocument(EmailEmbeddedObject item) {#removeFromDocument-com.groupdocs.watermark.contents.EmailEmbeddedObject-}
```
public void removeFromDocument(EmailEmbeddedObject item)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [EmailEmbeddedObject](../../com.groupdocs.watermark.contents/emailembeddedobject) |  |

