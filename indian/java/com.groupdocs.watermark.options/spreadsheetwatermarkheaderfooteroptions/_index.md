---
title: "SpreadsheetWatermarkHeaderFooterOptions"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "स्प्रेडशीट हेडर/फ़ूटर में वॉटरमार्क जोड़ते समय विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 57
url: /hi/java/com.groupdocs.watermark.options/spreadsheetwatermarkheaderfooteroptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public final class SpreadsheetWatermarkHeaderFooterOptions extends SpreadsheetWatermarkOptions
```

स्प्रेडशीट हेडर/फ़ूटर में वॉटरमार्क जोड़ते समय विकल्पों का प्रतिनिधित्व करता है।

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

निम्न उदाहरण दर्शाता है कि कैसे Excel कार्यपत्रक हेडर में टेक्स्ट वॉटरमार्क जोड़ा जाए।
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.xls", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    SpreadsheetWatermarkHeaderFooterOptions options = new SpreadsheetWatermarkHeaderFooterOptions();
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
|  | [SpreadsheetWatermarkHeaderFooterOptions()](#SpreadsheetWatermarkHeaderFooterOptions--) | एक नया उदाहरण आरंभ करता है `[SpreadsheetWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkheaderfooteroptions)` वर्ग का। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | वॉटरमार्क जोड़ने के लिए वर्कशीट का इंडेक्स प्राप्त करता है। |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | वॉटरमार्क जोड़ने के लिए वर्कशीट का इंडेक्स सेट करता है। |
|
### SpreadsheetWatermarkHeaderFooterOptions() {#SpreadsheetWatermarkHeaderFooterOptions--}
```
public SpreadsheetWatermarkHeaderFooterOptions()
```


एक नया उदाहरण आरंभ करता है `[SpreadsheetWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkheaderfooteroptions)` वर्ग का।


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

