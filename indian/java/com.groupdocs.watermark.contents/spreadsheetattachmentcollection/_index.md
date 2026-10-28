---
title: "SpreadsheetAttachmentCollection"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "Excel दस्तावेज़ में संलग्नकों के संग्रह का प्रतिनिधित्व करता है।"
type: docs
weight: 102
url: /hi/java/com.groupdocs.watermark.contents/spreadsheetattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class SpreadsheetAttachmentCollection extends RemoveOnlyListBase<SpreadsheetAttachment>
```

Excel दस्तावेज़ में संलग्नकों के संग्रह का प्रतिनिधित्व करता है।

यह संग्रह `[SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment)` प्रकार के आइटम शामिल करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addAttachment-byte---java.lang.String-byte---double-double-double-double-) | `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` में एक अटैचमेंट जोड़ता है। |
|
|  | [addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addLink-java.lang.String-byte---double-double-double-double-) | लिंक द्वारा एक अटैचमेंट जोड़ता है (दस्तावेज़ में संलग्न फ़ाइल की सामग्री नहीं होगी)। |
|
|  | [removeFromDocument(SpreadsheetAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-) | <br /> |

|
### addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addAttachment-byte---java.lang.String-byte---double-double-double-double-}
```
public final void addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


`[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)` में एक अटैचमेंट जोड़ता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | fileContent | byte[] | संलग्न की जाने वाली फ़ाइल की सामग्री। |
|
|  | sourceFullName | java.lang.String | संलग्न फ़ाइल का पूरा नाम (फ़ाइल एक्सटेंशन का उपयोग फ़ाइल खोलने के लिए उपयुक्त एप्लिकेशन निर्धारित करने में किया जाता है)। |
|
|  | previewImageContent | byte[] | संलग्न फ़ाइल पूर्वावलोकन छवि को बाइट ऐरे के रूप में। |
|
|  | x | double | अटैचमेंट फ्रेम का x-निर्देशांक (पॉइंट्स में)। |
|
|  | y | double | अटैचमेंट फ्रेम का y-निर्देशांक (पॉइंट्स में)। |
|
|  | width | double | संलग्न फ्रेम की चौड़ाई पॉइंट्स में। |
|
|  | height | double | संलग्न फ्रेम की ऊँचाई पॉइंट्स में। |
|

### addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addLink-java.lang.String-byte---double-double-double-double-}
```
public final void addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


लिंक द्वारा एक अटैचमेंट जोड़ता है (दस्तावेज़ में संलग्न फ़ाइल की सामग्री नहीं होगी)।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | sourceFullName | java.lang.String | लिंक की गई फ़ाइल का पथ। |
|
|  | previewImageContent | byte[] | संलग्न फ़ाइल पूर्वावलोकन छवि को बाइट ऐरे के रूप में। |
|
|  | x | double | अटैचमेंट फ्रेम का x-निर्देशांक (पॉइंट्स में)। |
|
|  | y | double | अटैचमेंट फ्रेम का y-निर्देशांक (पॉइंट्स में)। |
|
|  | width | double | संलग्न फ्रेम की चौड़ाई पॉइंट्स में। |
|
|  | height | double | संलग्न फ्रेम की ऊँचाई पॉइंट्स में। |
|

### removeFromDocument(SpreadsheetAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-}
```
public void removeFromDocument(SpreadsheetAttachment item)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment) |  |

