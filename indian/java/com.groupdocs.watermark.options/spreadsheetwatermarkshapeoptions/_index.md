---
title: "SpreadsheetWatermarkShapeOptions"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "स्प्रेडशीट वर्कशीट में आकार वॉटरमार्क जोड़ते समय विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 60
url: /hi/java/com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkBaseOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions)
```
public final class SpreadsheetWatermarkShapeOptions extends SpreadsheetWatermarkBaseOptions
```

स्प्रेडशीट वर्कशीट में आकार वॉटरमार्क जोड़ते समय विकल्पों का प्रतिनिधित्व करता है।

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

निम्न उदाहरण दर्शाता है कि Excel दस्तावेज़ के एक विशिष्ट वर्कशीट में वॉटरमार्क कैसे जोड़ें।
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.xls", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    SpreadsheetWatermarkShapeOptions options = new SpreadsheetWatermarkShapeOptions();
>    options.setWorksheetIndex(0);
>    
>    watermarker.save("D:\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ````


## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [SpreadsheetWatermarkShapeOptions()](#SpreadsheetWatermarkShapeOptions--) | `[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)` क्लास का नया उदाहरण प्रारंभ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | वॉटरमार्क जोड़ने के लिए वर्कशीट का इंडेक्स प्राप्त करता है। |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | वॉटरमार्क जोड़ने के लिए वर्कशीट का इंडेक्स सेट करता है। |
|
|  | [getEffects()](#getEffects--) | `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` या `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` का मान प्राप्त करता है, जो वॉटरमार्क पर लागू होने वाले प्रभावों के लिए है। |
|
|  | [setEffects(ISpreadsheetWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-) | `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` या `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` का मान प्राप्त या सेट करता है, जो वॉटरमार्क पर लागू होने वाले प्रभावों के लिए है। |
|
### SpreadsheetWatermarkShapeOptions() {#SpreadsheetWatermarkShapeOptions--}
```
public SpreadsheetWatermarkShapeOptions()
```


`[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)` क्लास का नया उदाहरण प्रारंभ करता है।


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


वॉटरमार्क जोड़ने के लिए वर्कशीट का इंडेक्स प्राप्त करता है।


**Returns:**
int - वॉटरमार्क जोड़ने के लिए वर्कशीट का इंडेक्स।

<br />

*** ** * ** ***

-1 means every worksheet.

<br />


### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


वॉटरमार्क जोड़ने के लिए वर्कशीट का इंडेक्स सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | वॉटरमार्क जोड़ने के लिए वर्कशीट का इंडेक्स। |

<br />

*** ** * ** ***

-1 means every worksheet.

<br />

|

### getEffects() {#getEffects--}
```
public final ISpreadsheetWatermarkEffects getEffects()
```


`[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` या `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` का मान प्राप्त करता है, जो वॉटरमार्क पर लागू होने वाले प्रभावों के लिए है।


**Returns:**
[ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) - The `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` or `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` for effects that should be applied to the watermark.

### setEffects(ISpreadsheetWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void setEffects(ISpreadsheetWatermarkEffects value)
```


`[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` या `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` का मान प्राप्त या सेट करता है, जो वॉटरमार्क पर लागू होने वाले प्रभावों के लिए है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) | वॉटरमार्क पर लागू होने वाले प्रभावों के लिए `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` या `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)`। |
|

