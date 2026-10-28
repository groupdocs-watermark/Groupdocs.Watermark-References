---
title: "WordProcessingHeaderFooterCollection"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "Word दस्तावेज़ में हेडर और फ़ूटर का संग्रह दर्शाता है।"
type: docs
weight: 132
url: /hi/java/com.groupdocs.watermark.contents/wordprocessingheaderfootercollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class WordProcessingHeaderFooterCollection extends ReadOnlyListBase<WordProcessingHeaderFooter>
```

Word दस्तावेज़ में हेडर और फ़ूटर का संग्रह दर्शाता है।

यह संग्रह `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` प्रकार के आइटम्स रखता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getByOfficeHeaderFooterType(int headerFooterType)](#getByOfficeHeaderFooterType-int-) | निर्दिष्ट प्रकार के हेडर या फुटर को प्राप्त करता है। |
|
|  | [linkToPrevious(boolean isLinkToPrevious)](#linkToPrevious-boolean-) | सभी हेडर और फुटर को संबंधित से लिंक या अनलिंक करता है |
पिछले सेक्शन में हेडर और फुटर।
|
### getByOfficeHeaderFooterType(int headerFooterType) {#getByOfficeHeaderFooterType-int-}
```
public final WordProcessingHeaderFooter getByOfficeHeaderFooterType(int headerFooterType)
```


निर्दिष्ट प्रकार के हेडर या फुटर को प्राप्त करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | headerFooterType | int | एक `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` मान जो प्राप्त करने के लिए हेडर/फुटर के प्रकार को निर्दिष्ट करता है। |
|

**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` of specified type.

### linkToPrevious(boolean isLinkToPrevious) {#linkToPrevious-boolean-}
```
public final void linkToPrevious(boolean isLinkToPrevious)
```


सभी हेडर और फुटर को संबंधित से लिंक या अनलिंक करता है
पिछले सेक्शन में हेडर और फुटर।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | isLinkToPrevious | boolean | पिछले सेक्शन से हेडर और फुटर को लिंक करने के लिए true; उन्हें अनलिंक करने के लिए false। |
|

