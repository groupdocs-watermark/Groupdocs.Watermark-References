---
title: "Attachment"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "दस्तावेज़ से संलग्न फ़ाइल का प्रतिनिधित्व करता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.watermark.common/attachment/
---
**Inheritance:**
java.lang.Object
```
public abstract class Attachment
```

दस्तावेज़ से संलग्न फ़ाइल का प्रतिनिधित्व करता है।

**Learn more**

* [Email attachments](../https://docs.groupdocs.com/display/watermarkjava/Email+attachments)
* [Attachments in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Attachments+in+PDF+document)
* [Working with spreadsheet document attachments](../https://docs.groupdocs.com/display/watermarkjava/Working+with+spreadsheet+document+attachments)

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getDocumentInfo()](#getDocumentInfo--) | संलग्न फ़ाइल में संग्रहीत दस्तावेज़ की जानकारी प्राप्त करता है। |
|
|  | [getContent()](#getContent--) | संलग्न फ़ाइल की सामग्री प्राप्त करता है। |
|
|  | [setContent(byte[] value)](#setContent-byte---) | संलग्न फ़ाइल की सामग्री सेट करता है। |
|
|  | [createWatermarker()](#createWatermarker--) | संलग्न फ़ाइल से सामग्री लोड करता है। |
|
|  | [createWatermarker(LoadOptions loadOptions)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-) | निर्दिष्ट लोड विकल्पों के साथ संलग्न फ़ाइल से सामग्री लोड करता है। |
|
|  | [createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | निर्दिष्ट लोड विकल्पों और सेटिंग्स के साथ संलग्न फ़ाइल से सामग्री लोड करता है। |
|
|  | [getContentStream()](#getContentStream--) | संलग्न फ़ाइल से स्ट्रीम प्राप्त करता है। |
|
|  | [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) | स्ट्रीम से संलग्न फ़ाइल को अपडेट करता है। |
|
|  | [updateContent(Watermarker updatedVersion)](#updateContent-com.groupdocs.watermark.Watermarker-) | संलग्न सामग्री को अपडेट करता है। |
|
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


संलग्न फ़ाइल में संग्रहीत दस्तावेज़ की जानकारी प्राप्त करता है।


**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo) - The `[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)` instance that contains detected information.

### getContent() {#getContent--}
```
public abstract byte[] getContent()
```


संलग्न फ़ाइल की सामग्री प्राप्त करता है।


**Returns:**
byte[] - संलग्न फ़ाइल की सामग्री।

### setContent(byte[] value) {#setContent-byte---}
```
public abstract void setContent(byte[] value)
```


संलग्न फ़ाइल की सामग्री सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | byte[] | संलग्न फ़ाइल की सामग्री। |
|

### createWatermarker() {#createWatermarker--}
```
public final Watermarker createWatermarker()
```


संलग्न फ़ाइल से सामग्री लोड करता है।


**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### createWatermarker(LoadOptions loadOptions) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions)
```


निर्दिष्ट लोड विकल्पों के साथ संलग्न फ़ाइल से सामग्री लोड करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | संलग्न सामग्री लोड करते समय उपयोग करने के अतिरिक्त विकल्प। |
|

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)
```


निर्दिष्ट लोड विकल्पों और सेटिंग्स के साथ संलग्न फ़ाइल से सामग्री लोड करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | संलग्न सामग्री लोड करते समय उपयोग करने के अतिरिक्त विकल्प। |
|
|  | watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | लोड किए गए दस्तावेज़ के साथ काम करते समय उपयोग करने के लिए अतिरिक्त सेटिंग्स। |
|

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


संलग्न फ़ाइल से स्ट्रीम प्राप्त करता है।


**Returns:**
com.aspose.ms.System.IO.Stream - फ़ाइल सामग्री पढ़ने के लिए स्ट्रीम।

### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


स्ट्रीम से संलग्न फ़ाइल को अपडेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | संलग्न फ़ाइल को अपडेट करने के लिए स्ट्रीम। |
|

### updateContent(Watermarker updatedVersion) {#updateContent-com.groupdocs.watermark.Watermarker-}
```
public final void updateContent(Watermarker updatedVersion)
```


संलग्न सामग्री को अपडेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | updatedVersion | [Watermarker](../../com.groupdocs.watermark/watermarker) | सामग्री का अपडेटेड संस्करण। |
|

