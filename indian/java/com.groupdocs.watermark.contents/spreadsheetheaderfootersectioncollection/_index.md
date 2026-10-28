---
title: "SpreadsheetHeaderFooterSectionCollection"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "हेडर/फ़ूटर सेक्शन के संग्रह का प्रतिनिधित्व करता है।"
type: docs
weight: 112
url: /hi/java/com.groupdocs.watermark.contents/spreadsheetheaderfootersectioncollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class SpreadsheetHeaderFooterSectionCollection extends ReadOnlyListBase<SpreadsheetHeaderFooterSection>
```

हेडर/फ़ूटर सेक्शन के संग्रह का प्रतिनिधित्व करता है।

यह संग्रह `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` प्रकार के आइटम्स रखता है।

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [SpreadsheetHeaderFooterSectionCollection(SpreadsheetHeaderFooter headerFooter)](#SpreadsheetHeaderFooterSectionCollection-com.groupdocs.watermark.contents.SpreadsheetHeaderFooter-) | <br /> |

|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getBySpreadsheetHeaderFooterSectionType(int headerFooterSectionType)](#getBySpreadsheetHeaderFooterSectionType-int-) | निर्दिष्ट प्रकार के हेडर/फ़ूटर सेक्शन को प्राप्त करता है। |
|
### SpreadsheetHeaderFooterSectionCollection(SpreadsheetHeaderFooter headerFooter) {#SpreadsheetHeaderFooterSectionCollection-com.groupdocs.watermark.contents.SpreadsheetHeaderFooter-}
```
public SpreadsheetHeaderFooterSectionCollection(SpreadsheetHeaderFooter headerFooter)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| headerFooter | [SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter) |  |

### getBySpreadsheetHeaderFooterSectionType(int headerFooterSectionType) {#getBySpreadsheetHeaderFooterSectionType-int-}
```
public final SpreadsheetHeaderFooterSection getBySpreadsheetHeaderFooterSectionType(int headerFooterSectionType)
```


निर्दिष्ट प्रकार के हेडर/फ़ूटर सेक्शन को प्राप्त करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | headerFooterSectionType | int | एक `[SpreadsheetHeaderFooterSectionType](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersectiontype)` मान जो प्राप्त करने वाले सेक्शन के प्रकार को निर्दिष्ट करता है। |
|

**Returns:**
[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection) - The `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` of specified type.

