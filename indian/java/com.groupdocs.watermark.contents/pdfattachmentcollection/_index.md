---
title: "PdfAttachmentCollection"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "PDF दस्तावेज़ में अटैचमेंट के संग्रह का प्रतिनिधित्व करता है।"
type: docs
weight: 59
url: /hi/java/com.groupdocs.watermark.contents/pdfattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class PdfAttachmentCollection extends RemoveOnlyListBase<PdfAttachment>
```

PDF दस्तावेज़ में अटैचमेंट के संग्रह का प्रतिनिधित्व करता है।

यह संग्रह `[PdfAttachment](../../com.groupdocs.watermark.contents/pdfattachment)` प्रकार के आइटम्स रखता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [add(byte[] fileContent, String name, String description)](#add-byte---java.lang.String-java.lang.String-) | `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)` में एक संलग्नक जोड़ता है। |
|
|  | [removeFromDocument(PdfAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.PdfAttachment-) | <br /> |

|
### add(byte[] fileContent, String name, String description) {#add-byte---java.lang.String-java.lang.String-}
```
public final void add(byte[] fileContent, String name, String description)
```


`[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)` में एक संलग्नक जोड़ता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | fileContent | byte[] | संलग्न की जाने वाली फ़ाइल की सामग्री। |
|
|  | name | java.lang.String | फ़ाइल का नाम। |
|
|  | description | java.lang.String | फ़ाइल का विवरण। |
|

### removeFromDocument(PdfAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.PdfAttachment-}
```
public void removeFromDocument(PdfAttachment item)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [PdfAttachment](../../com.groupdocs.watermark.contents/pdfattachment) |  |

